.. sip:method-description::
    :status: todo
    :pysig: 6675617fcf22ff5ce9ca047122c3dfb6
    :realsig: (const QByteArray&,QSsl::KeyAlgorithm,QSsl::EncodingFormat,QSsl::KeyType,const QByteArray&)
    :digest: edd16b074c2bdc4b39c6444de5316d86

Constructs a :sip:ref:`~PyQt5.QtNetwork.QSslKey` by decoding the string in the byte array *encoded* using a specified *algorithm* and *encoding* format. *type* specifies whether the key is public or private.

If the key is encrypted then *passPhrase* is used to decrypt it.

After construction, use :sip:ref:`~PyQt5.QtNetwork.QSslKey.isNull` to check if *encoded* contained a valid key.
