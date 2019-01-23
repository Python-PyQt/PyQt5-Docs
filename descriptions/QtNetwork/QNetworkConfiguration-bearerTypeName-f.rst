.. sip:method-description::
    :status: todo
    :pysig: 341be97d9aff90c9978347f66f945b77
    :realsig: () const
    :digest: d25891ef971e4aa27c0dc33011f51b56

Returns the type of bearer used by this network configuration as a string.

The string is not translated and therefore can not be shown to the user. The subsequent table shows the fixed mappings between :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.BearerType.BearerType` and the bearer type name for known types. If the :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.BearerType.BearerType` is unknown this function may return additional information if it is available; otherwise an empty string will be returned.

+------------------------------------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------+
| :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.BearerType.BearerType`      | Value                                                                                                                      |
+==============================================================================+============================================================================================================================+
| :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.BearerType.BearerUnknown`   | The session is based on an unknown or unspecified bearer type. The value of the string returned describes the bearer type. |
+------------------------------------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------+
| :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.BearerType.BearerEthernet`  | Ethernet                                                                                                                   |
+------------------------------------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------+
| :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.BearerType.BearerWLAN`      | WLAN                                                                                                                       |
+------------------------------------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------+
| :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.BearerType.Bearer2G`        | 2G                                                                                                                         |
+------------------------------------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------+
| Bearer3G                                                                     | 3G                                                                                                                         |
+------------------------------------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------+
| Bearer4G                                                                     | 4G                                                                                                                         |
+------------------------------------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------+
| :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.BearerType.BearerCDMA2000`  | CDMA2000                                                                                                                   |
+------------------------------------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------+
| :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.BearerType.BearerWCDMA`     | WCDMA                                                                                                                      |
+------------------------------------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------+
| :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.BearerType.BearerHSPA`      | HSPA                                                                                                                       |
+------------------------------------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------+
| :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.BearerType.BearerBluetooth` | Bluetooth                                                                                                                  |
+------------------------------------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------+
| :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.BearerType.BearerWiMAX`     | WiMAX                                                                                                                      |
+------------------------------------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------+
| BearerEVDO                                                                   | EVDO                                                                                                                       |
+------------------------------------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------+
| BearerLTE                                                                    | LTE                                                                                                                        |
+------------------------------------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------+

This function returns an empty string if this is an invalid configuration, a network configuration of type :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.Type.ServiceNetwork` or :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.Type.UserChoice`.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.bearerType`.
