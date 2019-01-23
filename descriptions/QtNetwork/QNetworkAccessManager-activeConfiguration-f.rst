.. sip:method-description::
    :status: todo
    :pysig: 1a4561fce4f2501e2f79f13455e63181
    :realsig: () const
    :digest: 046926f3ec407ba6b83c03c22f8bea02

Returns the current active network configuration.

If the network configuration returned by :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager.configuration` is of type :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.Type.ServiceNetwork` this function will return the current active child network configuration of that configuration. Otherwise returns the same network configuration as :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager.configuration`.

Use this function to return the actual network configuration currently in use by the network session.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager.configuration`.
