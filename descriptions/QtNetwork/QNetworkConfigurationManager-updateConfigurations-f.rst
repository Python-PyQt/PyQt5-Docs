.. sip:method-description::
    :status: todo
    :pysig: d41d8cd98f00b204e9800998ecf8427e
    :realsig: ()
    :digest: 049bf1399c6f308b851e9ef09d44056c

Initiates an update of all configurations. This may be used to initiate WLAN scans or other time consuming updates which may be required to obtain the correct state for configurations.

This call is asynchronous. On completion of this update the :sip:ref:`~PyQt5.QtNetwork.QNetworkConfigurationManager.updateCompleted` signal is emitted. If new configurations are discovered or old ones were removed or changed the update process may trigger the emission of one or multiple :sip:ref:`~PyQt5.QtNetwork.QNetworkConfigurationManager.configurationAdded`, :sip:ref:`~PyQt5.QtNetwork.QNetworkConfigurationManager.configurationRemoved` and :sip:ref:`~PyQt5.QtNetwork.QNetworkConfigurationManager.configurationChanged` signals.

If a configuration state changes as a result of this update all existing :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration` instances are updated automatically.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkConfigurationManager.allConfigurations`.
