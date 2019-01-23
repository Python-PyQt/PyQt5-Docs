.. sip:method-description::
    :status: todo
    :pysig: d41d8cd98f00b204e9800998ecf8427e
    :realsig: ()
    :digest: 5bb897919ac6025c43166b82f6855c0a

Creates an open session which increases the session counter on the underlying network interface. The system will not terminate a network interface until the session reference counter reaches zero. Therefore an open session allows an application to register its use of the interface.

As a result of calling  the interface will be started if it is not connected/up yet. Some platforms may not provide support for out-of-process sessions. On such platforms the session counter ignores any sessions held by another process. The platform capabilities can be detected via :sip:ref:`~PyQt5.QtNetwork.QNetworkConfigurationManager.capabilities`.

Note that this call is asynchronous. Depending on the outcome of this call the results can be enquired by connecting to the :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.stateChanged`, :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.opened` or :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.error` signals.

It is not a requirement to open a session in order to monitor the underlying network interface.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.close`, :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.stop`, :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.isOpen`.
