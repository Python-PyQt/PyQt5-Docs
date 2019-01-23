.. sip:method-description::
    :status: todo
    :pysig: 856011945010d069512fe5eeab11a4f0
    :realsig: (const QString&,QSsl::SslProtocol)
    :digest: c724fa978982bae8d026ed9c68455926

Constructs a :sip:ref:`~PyQt5.QtNetwork.QSslCipher` object for the cipher determined by *name* and *protocol*. The constructor accepts only supported ciphers (i.e., the *name* and *protocol* must identify a cipher in the list of ciphers returned by :sip:ref:`~PyQt5.QtNetwork.QSslSocket.supportedCiphers`).

You can call :sip:ref:`~PyQt5.QtNetwork.QSslCipher.isNull` after construction to check if *name* and *protocol* correctly identified a supported cipher.
