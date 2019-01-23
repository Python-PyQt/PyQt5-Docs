.. sip:class-description::
    :status: todo
    :brief: Access to the window system clipboard
    :digest: 99670a490800a2eb982a8b7d34bc7d0a

The :sip:ref:`~PyQt5.QtGui.QClipboard` class provides access to the window system clipboard.

The clipboard offers a simple mechanism to copy and paste data between applications.

:sip:ref:`~PyQt5.QtGui.QClipboard` supports the same data types that :sip:ref:`~PyQt5.QtGui.QDrag` does, and uses similar mechanisms. For advanced clipboard usage read `Drag and Drop <https://doc.qt.io/qt-5/dnd.html>`_.

There is a single :sip:ref:`~PyQt5.QtGui.QClipboard` object in an application, accessible as :sip:ref:`~PyQt5.QtGui.QGuiApplication.clipboard`.

Example:

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-code-src_gui_kernel_qclipboard.py
    :lines: 54-57

:sip:ref:`~PyQt5.QtGui.QClipboard` features some convenience functions to access common data types: :sip:ref:`~PyQt5.QtGui.QClipboard.setText` allows the exchange of Unicode text and :sip:ref:`~PyQt5.QtGui.QClipboard.setPixmap` and :sip:ref:`~PyQt5.QtGui.QClipboard.setImage` allows the exchange of QPixmaps and QImages between applications. The :sip:ref:`~PyQt5.QtGui.QClipboard.setMimeData` function is the ultimate in flexibility: it allows you to add any :sip:ref:`~PyQt5.QtCore.QMimeData` into the clipboard. There are corresponding getters for each of these, e.g. :sip:ref:`~PyQt5.QtGui.QClipboard.text`, :sip:ref:`~PyQt5.QtGui.QClipboard.image` and :sip:ref:`~PyQt5.QtGui.QClipboard.pixmap`. You can clear the clipboard by calling :sip:ref:`~PyQt5.QtGui.QClipboard.clear`.

A typical example of the use of these functions follows:

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-droparea.py

.. _qclipboard-notes-for-x11-users:

Notes for X11 Users
-------------------

* The X11 Window System has the concept of a separate selection and clipboard. When text is selected, it is immediately available as the global mouse selection. The global mouse selection may later be copied to the clipboard. By convention, the middle mouse button is used to paste the global mouse selection.

* X11 also has the concept of ownership; if you change the selection within a window, X11 will only notify the owner and the previous owner of the change, i.e. it will not notify all applications that the selection or clipboard data changed.

* Lastly, the X11 clipboard is event driven, i.e. the clipboard will not function properly if the event loop is not running. Similarly, it is recommended that the contents of the clipboard are stored or retrieved in direct response to user-input events, e.g. mouse button or key presses and releases. You should not store or retrieve the clipboard contents in response to timer or non-user-input events.

* Since there is no standard way to copy and paste files between applications on X11, various MIME types and conventions are currently in use. For instance, Nautilus expects files to be supplied with a ``x-special/gnome-copied-files`` MIME type with data beginning with the cut/copy action, a newline character, and the URL of the file.

.. _qclipboard-notes-for-macos-users:

Notes for macOS Users
---------------------

`macOS <https://doc.qt.io/qt-5/qtwebengine-platform-notes.html#macos>`_ supports a separate find buffer that holds the current search string in Find operations. This find clipboard can be accessed by specifying the :sip:ref:`~PyQt5.QtGui.QClipboard.Mode.FindBuffer` mode.

.. _qclipboard-notes-for-windows-and-macos-users:

Notes for Windows and macOS Users
---------------------------------

* Windows and `macOS <https://doc.qt.io/qt-5/qtwebengine-platform-notes.html#macos>`_ do not support the global mouse selection; they only supports the global clipboard, i.e. they only add text to the clipboard when an explicit copy or cut is made.

* Windows and `macOS <https://doc.qt.io/qt-5/qtwebengine-platform-notes.html#macos>`_ does not have the concept of ownership; the clipboard is a fully global resource so all applications are notified of changes.

.. _qclipboard-notes-for-universal-windows-platform-users:

Notes for Universal Windows Platform Users
------------------------------------------

* The Universal Windows Platform only allows to query the clipboard in case the application is active and an application window has focus. Accessing the clipboard data when in background will fail due to access denial.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QGuiApplication`.
