.. sip:method-description::
    :status: todo
    :pysig: b4fb74d483d7ad5749c58c4b18a6e17b
    :realsig: (const QByteArray&) const
    :digest: fcf0283e67440c913fc622f9d328308d

Returns a string containing an HTML representation of the document.

The *encoding* parameter specifies the value for the charset attribute in the html header. For example if 'utf-8' is specified then the beginning of the generated html will look like this:

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-code-src_gui_text_qtextdocument.py
    :lines: 54-54

If no encoding is specified then no such meta information is generated.

If you later on convert the returned html string into a byte array for transmission over a network or when saving to disk you should specify the encoding you're going to use for the conversion to a byte array here.

.. seealso:: `Supported HTML Subset <https://doc.qt.io/qt-5/richtext-html-subset.html>`_.
