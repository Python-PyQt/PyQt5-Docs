.. sip:class-description::
    :status: todo
    :brief: Helper class for XML readers which want to include namespace support
    :digest: 83fd842866a8f329a7a47dc964897e1f

The :sip:ref:`~PyQt5.QtXml.QXmlNamespaceSupport` class is a helper class for XML readers which want to include namespace support.

You can set the prefix for the current namespace with :sip:ref:`~PyQt5.QtXml.QXmlNamespaceSupport.setPrefix`, and get the list of current prefixes (or those for a given URI) with :sip:ref:`~PyQt5.QtXml.QXmlNamespaceSupport.prefixes`. The namespace URI is available from :sip:ref:`~PyQt5.QtXml.QXmlNamespaceSupport.uri`. Use :sip:ref:`~PyQt5.QtXml.QXmlNamespaceSupport.pushContext` to start a new namespace context, and :sip:ref:`~PyQt5.QtXml.QXmlNamespaceSupport.popContext` to return to the previous namespace context. Use :sip:ref:`~PyQt5.QtXml.QXmlNamespaceSupport.splitName` or :sip:ref:`~PyQt5.QtXml.QXmlNamespaceSupport.processName` to split a name into its prefix and local name.

.. seealso:: `Namespace Support via Features <https://doc.qt.io/qt-5/xml-sax.html#namespace-support-via-features>`_.
