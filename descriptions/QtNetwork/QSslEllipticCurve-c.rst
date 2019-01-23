.. sip:class-description::
    :status: todo
    :brief: Represents an elliptic curve for use by elliptic-curve cipher algorithms
    :digest: 2b71648b52d5b576d9198793b8d366eb

Represents an elliptic curve for use by elliptic-curve cipher algorithms.

The class :sip:ref:`~PyQt5.QtNetwork.QSslEllipticCurve` represents an elliptic curve for use by elliptic-curve cipher algorithms.

Elliptic curves can be constructed from a "short name" (SN) (fromShortName()), and by a call to QSslConfiguration::supportedEllipticCurves().

:sip:ref:`~PyQt5.QtNetwork.QSslEllipticCurve` instances can be compared for equality and can be used as keys in QHash and QSet. They cannot be used as key in a QMap.
