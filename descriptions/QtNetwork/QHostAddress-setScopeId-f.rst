.. sip:method-description::
    :status: todo
    :pysig: 341be97d9aff90c9978347f66f945b77
    :realsig: (const QString&)
    :digest: 9ccacead79554a869b93b02f94c96de4

Sets the IPv6 scope ID of the address to *id*. If the address protocol is not IPv6, this function does nothing. The scope ID may be set as an interface name (such as "eth0" or "en1") or as an integer representing the interface index. If *id* is an interface name, :sip:ref:`~PyQt5.QtNetwork` will convert to an interface index using QNetworkInterface::interfaceIndexFromName() before calling the operating system networking functions.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QHostAddress.scopeId`, :sip:ref:`~PyQt5.QtNetwork.QNetworkInterface`, :sip:ref:`~PyQt5.QtNetwork.QNetworkInterface.interfaceFromName`.
