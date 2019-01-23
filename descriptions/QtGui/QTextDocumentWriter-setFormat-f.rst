.. sip:method-description::
    :status: todo
    :pysig: f4b16e65d42ad609ac1af344eee47372
    :realsig: (const QByteArray&)
    :digest: a761ea022fce63d61051bf0daccaebc4

Sets the format used to write documents to the *format* specified. *format* is a case insensitive text string. For example:

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-code-src_gui_text_qtextdocumentwriter.py
    :lines: 54-55

You can call :sip:ref:`~PyQt5.QtGui.QTextDocumentWriter.supportedDocumentFormats` for the full list of formats :sip:ref:`~PyQt5.QtGui.QTextDocumentWriter` supports.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QTextDocumentWriter.format`.
