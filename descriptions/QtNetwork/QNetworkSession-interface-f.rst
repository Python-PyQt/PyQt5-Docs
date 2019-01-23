.. sip:method-description::
    :status: todo
    :pysig: f26d8363b0fa5bd8f8bda48d3005be38
    :realsig: () const
    :digest: 45c062831b79cd2887e1619b6957e90d

Returns the network interface that is used by this session.

This function only returns a valid :sip:ref:`~PyQt5.QtNetwork.QNetworkInterface` when this session is :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.State.Connected`.

The returned interface may change as a result of a roaming process.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.state`.
