.. sip:method-description::
    :status: todo
    :pysig: d41d8cd98f00b204e9800998ecf8427e
    :realsig: ()
    :digest: 5e5718dbead5d8a029b81c8bea647ab9

Invalidates all open sessions against the network interface and therefore stops the underlying network interface. This function always changes the session's :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.state` flag to :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.State.Disconnected`.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.open`, :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.close`.
