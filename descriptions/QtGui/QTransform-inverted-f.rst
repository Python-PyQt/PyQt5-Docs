.. sip:method-description::
    :status: todo
    :pysig: 66ca6b7c7d4b639d14f694c4febbae30
    :realsig: (bool*) const
    :digest: b9bcabe949bccef143ff3f8fe9f2eebb

Returns an inverted copy of this matrix.

If the matrix is singular (not invertible), the returned matrix is the identity matrix. If *invertible* is valid (i.e. not 0), its value is set to true if the matrix is invertible, otherwise it is set to false.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QTransform.isInvertible`.
