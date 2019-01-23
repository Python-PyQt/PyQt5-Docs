.. sip:method-description::
    :status: todo
    :pysig: f4b16e65d42ad609ac1af344eee47372
    :realsig: (const QByteArray&)
    :digest: 4027a88e6709a6fb4dab16d3c66611a0

Sets the pre shared key to *preSharedKey*.

**Note:** it is possible to set a key whose length is greater than the :sip:ref:`~PyQt5.QtNetwork.QSslPreSharedKeyAuthenticator.maximumPreSharedKeyLength`; in this case, only the first :sip:ref:`~PyQt5.QtNetwork.QSslPreSharedKeyAuthenticator.maximumPreSharedKeyLength` bytes will be actually sent to the server.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QSslPreSharedKeyAuthenticator.preSharedKey`, :sip:ref:`~PyQt5.QtNetwork.QSslPreSharedKeyAuthenticator.maximumPreSharedKeyLength`.
