.. sip:method-description::
    :status: todo
    :pysig: fa7153f7ed1cb6c0fcf2ffb2fac21748
    :realsig: () const
    :digest: 70497e1224621b6903f1bedec2423039

Returns the amount of data received in bytes; otherwise 0.

This field value includes the usage across all open network sessions which use the same network interface.

If the session is based on a service network configuration the number of sent bytes across all active member configurations are returned.

This function may not always be supported on all platforms and returns 0. The platform capability can be detected via :sip:ref:`~PyQt5.QtNetwork.QNetworkConfigurationManager.Capability.DataStatistics`.

**Note:** On some platforms this function may run the main event loop.
