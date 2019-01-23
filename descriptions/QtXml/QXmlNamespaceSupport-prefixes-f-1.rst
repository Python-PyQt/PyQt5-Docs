.. sip:method-description::
    :status: todo
    :pysig: 04d56410d49d4df839f0b7860b7e4790
    :realsig: (const QString&) const
    :digest: c45003b088acb9a0801267fd4a15bef3

This is an overloaded function.

Returns a list of all prefixes currently declared for the namespace URI *uri*.

The "xml:" prefix is included. If you only want one prefix that is mapped to the namespace URI, and you don't care which one you get, use the :sip:ref:`~PyQt5.QtXml.QXmlNamespaceSupport.prefix` function instead.

Note: The empty (default) prefix is never included in this list; to check for the presence of a default namespace, call :sip:ref:`~PyQt5.QtXml.QXmlNamespaceSupport.uri` with "" as the argument.
