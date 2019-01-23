.. sip:method-description::
    :status: todo
    :pysig: d677f422557c9408b1c3796a2a851dba
    :realsig: ()
    :digest: 967e9be98bddb4d18d8fef5babf67141

Use QSslConfiguration::systemDefaultCaCertificates instead.

This function provides the CA certificate database provided by the operating system. The CA certificate database returned by this function is used to initialize the database returned by :sip:ref:`~PyQt5.QtNetwork.QSslSocket.defaultCaCertificates`. You can replace that database with your own with :sip:ref:`~PyQt5.QtNetwork.QSslSocket.setDefaultCaCertificates`.

**Note:** : On OS X, only certificates that are either trusted for all purposes or trusted for the purpose of SSL in the keychain will be returned.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QSslSocket.caCertificates`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.defaultCaCertificates`, :sip:ref:`~PyQt5.QtNetwork.QSslSocket.setDefaultCaCertificates`.
