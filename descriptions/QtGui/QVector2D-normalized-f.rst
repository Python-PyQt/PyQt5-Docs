.. sip:method-description::
    :status: todo
    :pysig: e2e570fda027b3521458b67fc6523656
    :realsig: () const
    :digest: 2a38c638ce8efb855535699a961a3c86

Returns the normalized unit vector form of this vector.

If this vector is null, then a null vector is returned. If the length of the vector is very close to 1, then the vector will be returned as-is. Otherwise the normalized form of the vector of length 1 will be returned.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QVector2D.length`, :sip:ref:`~PyQt5.QtGui.QVector2D.normalize`.
