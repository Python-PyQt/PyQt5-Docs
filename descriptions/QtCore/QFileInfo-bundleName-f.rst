.. sip:method-description::
    :status: todo
    :pysig: 341be97d9aff90c9978347f66f945b77
    :realsig: () const
    :digest: d99f1b18b90ccd12f84502e134209550

Returns the name of the bundle.

On `macOS <https://doc.qt.io/qt-5/qtwebengine-platform-notes.html#macos>`_ and iOS this returns the proper localized name for a bundle if the path :sip:ref:`~PyQt5.QtCore.QFileInfo.isBundle`. On all other platforms an empty QString is returned.

Example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_io_qfileinfo.py
    :lines: 116-117

.. seealso:: :sip:ref:`~PyQt5.QtCore.QFileInfo.isBundle`, :sip:ref:`~PyQt5.QtCore.QFileInfo.filePath`, :sip:ref:`~PyQt5.QtCore.QFileInfo.baseName`, :sip:ref:`~PyQt5.QtCore.QFileInfo.suffix`.
