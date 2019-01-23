.. sip:attribute-description::
    :status: todo
    :digest: a95f8c7dbe2553812c595746e977c09c

This macro expands a numeric value of the form 0xMMNNPP (MM = major, NN = minor, PP = patch) that specifies Qt's version number. For example, if you compile your application against Qt 4.1.2, the  macro will expand to 0x040102.

You can use  to use the latest Qt features where available.

Example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_global_qglobal.py
    :lines: 207-212

.. seealso:: :sip:ref:`~PyQt5.QtCore.QT_VERSION_STR`.
