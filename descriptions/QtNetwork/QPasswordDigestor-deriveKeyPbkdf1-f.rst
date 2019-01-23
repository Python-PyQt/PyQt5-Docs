.. sip:method-description::
    :status: todo
    :pysig: 0654d2524274890a26e116359159a4a4
    :realsig: (QCryptographicHash::Algorithm,const QByteArray&,const QByteArray&,int,quint64)
    :digest: 7041675c7ff146d82244ca16dbf54afa

Returns a hash computed using the PBKDF1-algorithm as defined in RFC 8018.

The function takes the *data* and *salt*, and then hashes it repeatedly for *iterations* iterations using the specified hash *algorithm*. If the resulting hash is longer than *dkLen* then it is truncated before it is returned.

This function only supports SHA-1 and MD5! The max output size is 160 bits (20 bytes) when using SHA-1, or 128 bits (16 bytes) when using MD5. Specifying a value for *dkLen* which is greater than this results in a warning and an empty :sip:ref:`~PyQt5.QtCore.QByteArray` is returned. To programmatically check this limit you can use :sip:ref:`~PyQt5.QtCore.QCryptographicHash.hashLength`. Furthermore: the *salt* must always be 8 bytes long!

**Note:** This function is provided for use with legacy applications and all new applications are recommended to use PBKDF2.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QPasswordDigestor.deriveKeyPbkdf2`, :sip:ref:`~PyQt5.QtCore.QCryptographicHash`, :sip:ref:`~PyQt5.QtCore.QCryptographicHash.hashLength`.
