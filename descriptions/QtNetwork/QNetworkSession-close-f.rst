.. sip:method-description::
    :status: todo
    :pysig: d41d8cd98f00b204e9800998ecf8427e
    :realsig: ()
    :digest: ff4b599331fe93f08036cf70e760ed0e

Decreases the session counter on the associated network configuration. If the session counter reaches zero the active network interface is shut down. This also means that :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.state` will only change from :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.State.Connected` to :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.State.Disconnected` if the current session was the last open session.

If the platform does not support out-of-process sessions calling this function does not stop the interface. In this case :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.stop` has to be used to force a shut down. The platform capabilities can be detected via :sip:ref:`~PyQt5.QtNetwork.QNetworkConfigurationManager.capabilities`.

Note that this call is asynchronous. Depending on the outcome of this call the results can be enquired by connecting to the :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.stateChanged`, :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.opened` or :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.error` signals.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.open`, :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.stop`, :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.isOpen`.
