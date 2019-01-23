.. sip:method-description::
    :status: todo
    :pysig: 1a4561fce4f2501e2f79f13455e63181
    :realsig: () const
    :digest: 6c15d231b7c442ad719db0b16381e368

Returns the default configuration to be used. This function always returns a discovered configuration; otherwise an invalid configuration.

In some cases it may be required to call :sip:ref:`~PyQt5.QtNetwork.QNetworkConfigurationManager.updateConfigurations` and wait for the :sip:ref:`~PyQt5.QtNetwork.QNetworkConfigurationManager.updateCompleted` signal before calling this function.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkConfigurationManager.allConfigurations`.
