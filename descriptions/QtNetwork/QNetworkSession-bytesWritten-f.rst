.. sip:method-description::
    :status: todo
    :pysig: fa7153f7ed1cb6c0fcf2ffb2fac21748
    :realsig: () const
    :digest: d916d1fdbf710b4ee71ec1e6053f2a09

Returns the amount of data sent in bytes; otherwise 0.

This field value includes the usage across all open network sessions which use the same network interface.

If the session is based on a service network configuration the number of sent bytes across all active member configurations are returned.

This function may not always be supported on all platforms and returns 0. The platform capability can be detected via :sip:ref:`~PyQt5.QtNetwork.QNetworkConfigurationManager.Capability.DataStatistics`.

**Note:** On some platforms this function may run the main event loop.
