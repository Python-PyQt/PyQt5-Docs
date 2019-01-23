.. sip:class-description::
    :status: todo
    :brief: Container for data that records information about its MIME type
    :digest: 9ccf085e4564e47f63255560c5ed80da

The :sip:ref:`~PyQt5.QtCore.QMimeData` class provides a container for data that records information about its MIME type.

:sip:ref:`~PyQt5.QtCore.QMimeData` is used to describe information that can be stored in the :sip:ref:`~PyQt5.QtGui.QClipboard`, and transferred via the `drag and drop <https://doc.qt.io/qt-5/dnd.html>`_ mechanism. :sip:ref:`~PyQt5.QtCore.QMimeData` objects associate the data that they hold with the corresponding MIME types to ensure that information can be safely transferred between applications, and copied around within the same application.

:sip:ref:`~PyQt5.QtCore.QMimeData` objects are usually created using ``new`` and supplied to :sip:ref:`~PyQt5.QtGui.QDrag` or :sip:ref:`~PyQt5.QtGui.QClipboard` objects. This is to enable Qt to manage the memory that they use.

A single :sip:ref:`~PyQt5.QtCore.QMimeData` object can store the same data using several different formats at the same time. The :sip:ref:`~PyQt5.QtCore.QMimeData.formats` function returns a list of the available formats in order of preference. The :sip:ref:`~PyQt5.QtCore.QMimeData.data` function returns the raw data associated with a MIME type, and :sip:ref:`~PyQt5.QtCore.QMimeData.setData` allows you to set the data for a MIME type.

For the most common MIME types, :sip:ref:`~PyQt5.QtCore.QMimeData` provides convenience functions to access the data:

+---------------------------------------------+----------------------------------------------+-------------------------------------------------+-------------------------+
| Tester                                      | Getter                                       | Setter                                          | MIME Types              |
+=============================================+==============================================+=================================================+=========================+
| :sip:ref:`~PyQt5.QtCore.QMimeData.hasText`  | :sip:ref:`~PyQt5.QtCore.QMimeData.text`      | :sip:ref:`~PyQt5.QtCore.QMimeData.setText`      | ``text/plain``          |
+---------------------------------------------+----------------------------------------------+-------------------------------------------------+-------------------------+
| :sip:ref:`~PyQt5.QtCore.QMimeData.hasHtml`  | :sip:ref:`~PyQt5.QtCore.QMimeData.html`      | :sip:ref:`~PyQt5.QtCore.QMimeData.setHtml`      | ``text/html``           |
+---------------------------------------------+----------------------------------------------+-------------------------------------------------+-------------------------+
| :sip:ref:`~PyQt5.QtCore.QMimeData.hasUrls`  | :sip:ref:`~PyQt5.QtCore.QMimeData.urls`      | :sip:ref:`~PyQt5.QtCore.QMimeData.setUrls`      | ``text/uri-list``       |
+---------------------------------------------+----------------------------------------------+-------------------------------------------------+-------------------------+
| :sip:ref:`~PyQt5.QtCore.QMimeData.hasImage` | :sip:ref:`~PyQt5.QtCore.QMimeData.imageData` | :sip:ref:`~PyQt5.QtCore.QMimeData.setImageData` | ``image/`` \*           |
+---------------------------------------------+----------------------------------------------+-------------------------------------------------+-------------------------+
| :sip:ref:`~PyQt5.QtCore.QMimeData.hasColor` | :sip:ref:`~PyQt5.QtCore.QMimeData.colorData` | :sip:ref:`~PyQt5.QtCore.QMimeData.setColorData` | ``application/x-color`` |
+---------------------------------------------+----------------------------------------------+-------------------------------------------------+-------------------------+

For example, if your write a widget that accepts URL drags, you would end up writing code like this:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_kernel_qmimedata.py
    :lines: 54-67

There are three approaches for storing custom data in a :sip:ref:`~PyQt5.QtCore.QMimeData` object:

#. Custom data can be stored directly in a :sip:ref:`~PyQt5.QtCore.QMimeData` object as a :sip:ref:`~PyQt5.QtCore.QByteArray` using :sip:ref:`~PyQt5.QtCore.QMimeData.setData`. For example:

   .. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_kernel_qmimedata.py
       :lines: 72-75

#. We can subclass :sip:ref:`~PyQt5.QtCore.QMimeData` and reimplement :sip:ref:`~PyQt5.QtCore.QMimeData.hasFormat`, :sip:ref:`~PyQt5.QtCore.QMimeData.formats`, and :sip:ref:`~PyQt5.QtCore.QMimeData.retrieveData`.

#. If the drag and drop operation occurs within a single application, we can subclass :sip:ref:`~PyQt5.QtCore.QMimeData` and add extra data in it, and use a  in the receiver's drop event handler. For example:

   .. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_kernel_qmimedata.py
       :lines: 80-87

.. _qmimedata-platform-specific-mime-types:

Platform-Specific MIME Types
----------------------------

On Windows, :sip:ref:`~PyQt5.QtCore.QMimeData.formats` will also return custom formats available in the MIME data, using the ``x-qt-windows-mime`` subtype to indicate that they represent data in non-standard formats. The formats will take the following form:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_kernel_qmimedata.py
    :lines: 92-92

The following are examples of custom MIME types:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_kernel_qmimedata.py
    :lines: 97-98

The ``value`` declaration of each format describes the way in which the data is encoded.

In some cases (e.g. dropping multiple email attachments), multiple data values are available. They can be accessed by adding an ``index`` value:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_kernel_qmimedata.py
    :lines: 124-125

On Windows, the MIME format does not always map directly to the clipboard formats. Qt provides QWinMime to map clipboard formats to open-standard MIME formats. Similarly, the QMacPasteboardMime maps MIME to Mac flavors.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QClipboard`, :sip:ref:`~PyQt5.QtGui.QDragEnterEvent`, :sip:ref:`~PyQt5.QtGui.QDragMoveEvent`, :sip:ref:`~PyQt5.QtGui.QDropEvent`, :sip:ref:`~PyQt5.QtGui.QDrag`, `Drag and Drop <https://doc.qt.io/qt-5/dnd.html>`_.
