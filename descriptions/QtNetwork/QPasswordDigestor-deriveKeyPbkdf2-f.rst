.. sip:method-description::
    :status: todo
    :pysig: 0654d2524274890a26e116359159a4a4
    :realsig: (QCryptographicHash::Algorithm,const QByteArray&,const QByteArray&,int,quint64)
    :digest: 9703a6dcc190c1d3acfd226cc285944c

Derive a key using the PBKDF2-algorithm as defined in RFC 8018.

This function takes the *data* and *salt*, and then applies HMAC-X, where the X is *algorithm*, repeatedly. It internally concatenates intermediate results to the final output until at least *dkLen* amount of bytes have been computed and it will execute HMAC-X *iterations* times each time a concatenation is required. The total number of times it will execute HMAC-X depends on *iterations*, *dkLen* and *algorithm* and can be calculated as ``iterations \* ceil(dkLen / QCryptographicHash::hashLength(algorithm))``.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QPasswordDigestor.deriveKeyPbkdf1`, :sip:ref:`~PyQt5.QtCore.QMessageAuthenticationCode`, :sip:ref:`~PyQt5.QtCore.QCryptographicHash`.
