.. sip:method-description::
    :status: todo
    :pysig: 1a4561fce4f2501e2f79f13455e63181
    :realsig: (const QNetworkConfiguration&)
    :digest: 6e85fb087f3838adc5c062f5d74dd7fb

Sets the network configuration that will be used when creating the :sip:ref:`~PyQt5.QtNetwork.QNetworkSession` to *config*.

The network configuration is used to create and open a network session before any request that requires network access is process. If no network configuration is explicitly set via this function the network configuration returned by :sip:ref:`~PyQt5.QtNetwork.QNetworkConfigurationManager.defaultConfiguration` will be used.

To restore the default network configuration set the network configuration to the value returned from :sip:ref:`~PyQt5.QtNetwork.QNetworkConfigurationManager.defaultConfiguration`.

Setting a network configuration means that the :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager` instance will only be using the specified one. In particular, if the default network configuration changes (upon e.g. Wifi being available), this new configuration needs to be enabled manually if desired.

.. literalinclude:: ../../../snippets/qtbase-src-network-doc-snippets-code-src_network_access_qnetworkaccessmanager.py
    :lines: 76-77

If an invalid network configuration is set, a network session will not be created. In this case network requests will be processed regardless, but may fail. For example:

.. literalinclude:: ../../../snippets/qtbase-src-network-doc-snippets-code-src_network_access_qnetworkaccessmanager.py
    :lines: 81-81

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager.configuration`, :sip:ref:`~PyQt5.QtNetwork.QNetworkSession`.
