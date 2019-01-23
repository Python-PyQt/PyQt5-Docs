.. sip:method-description::
    :status: todo
    :pysig: 341be97d9aff90c9978347f66f945b77
    :realsig: (const char*)
    :digest: 6a14f54c40d7fb4a88b96104bbaf3c39

Sets the codec for this stream to the :sip:ref:`~PyQt5.QtCore.QTextCodec` for the encoding specified by *codecName*. Common values for ``codecName`` include "ISO 8859-1", "UTF-8", and "UTF-16". If the encoding isn't recognized, nothing happens.

Example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_io_qtextstream.py
    :lines: 139-140

.. seealso:: :sip:ref:`~PyQt5.QtCore.QTextCodec.codecForName`, :sip:ref:`~PyQt5.QtCore.QTextStream.setLocale`.
