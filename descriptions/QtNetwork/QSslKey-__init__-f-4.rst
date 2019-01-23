.. sip:method-description::
    :status: todo
    :pysig: d02f9d00a83347af4a2f9f1757a619d7
    :realsig: (QIODevice*,QSsl::KeyAlgorithm,QSsl::EncodingFormat,QSsl::KeyType,const QByteArray&)
    :digest: 7e5651ec49e4e95e1aa7fd9793ed922a

Constructs a :sip:ref:`~PyQt5.QtNetwork.QSslKey` by reading and decoding data from a *device* using a specified *algorithm* and *encoding* format. *type* specifies whether the key is public or private.

If the key is encrypted then *passPhrase* is used to decrypt it.

After construction, use :sip:ref:`~PyQt5.QtNetwork.QSslKey.isNull` to check if *device* provided a valid key.
