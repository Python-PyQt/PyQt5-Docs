.. sip:method-description::
    :status: todo
    :pysig: 6359afdf86b9ec14316ea3f79e266b65
    :realsig: (const QByteArray&)
    :digest: 6ea7ebd6740c6875ed4b727150d15858

Constructs a read-only data stream that operates on byte array *a*. Use :sip:ref:`~PyQt5.QtCore.QDataStream`\ (\ :sip:ref:`~PyQt5.QtCore.QByteArray`\*, int) if you want to write to a byte array.

Since :sip:ref:`~PyQt5.QtCore.QByteArray` is not a :sip:ref:`~PyQt5.QtCore.QIODevice` subclass, internally a :sip:ref:`~PyQt5.QtCore.QBuffer` is created to wrap the byte array.
