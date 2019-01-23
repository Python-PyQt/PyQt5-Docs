.. sip:method-description::
    :status: todo
    :pysig: 77f0322f563b7821a9614252a804db51
    :realsig: ()
    :digest: dcd030b583d5929e7a2be0d8a7713681

Returns the default SSL configuration to be used in new SSL connections.

The default SSL configuration consists of:

* no local certificate and no private key

* protocol :sip:ref:`~PyQt5.QtNetwork.QSsl.SslProtocol.SecureProtocols`

* the system's default CA certificate list

* the cipher list equal to the list of the SSL libraries' supported SSL ciphers that are 128 bits or more

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QSslSocket.supportedCiphers`, :sip:ref:`~PyQt5.QtNetwork.QSslConfiguration.setDefaultConfiguration`.
