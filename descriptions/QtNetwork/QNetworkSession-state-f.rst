.. sip:method-description::
    :status: todo
    :pysig: ff8342c74b27ce2952e37c62b6a2f79b
    :realsig: () const
    :digest: bacfa2e095898bf5a8c460af37362192

Returns the state of the session.

If the session is based on a single access point configuration the state of the session is the same as the state of the associated network interface. Therefore a network session object can be used to monitor network interfaces.

A :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.Type.ServiceNetwork` based session summarizes the state of all its children and therefore returns the :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.State.Connected` state if at least one of the service network's :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.children` configurations is active.

Note that it is not required to hold an open session in order to obtain the network interface state. A connected but closed session may be used to monitor network interfaces whereas an open and connected session object may prevent the network interface from being shut down.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.error`, :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.stateChanged`.
