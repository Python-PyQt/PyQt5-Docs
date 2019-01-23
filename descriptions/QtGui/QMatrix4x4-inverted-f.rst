.. sip:method-description::
    :status: todo
    :pysig: 8103b777fc92b83461fd883c6b3088e6
    :realsig: (bool*) const
    :digest: 377d024f4ba4a5de8c105314f0cf5213

Returns the inverse of this matrix. Returns the identity if this matrix cannot be inverted; i.e. :sip:ref:`~PyQt5.QtGui.QMatrix4x4.determinant` is zero. If *invertible* is not null, then true will be written to that location if the matrix can be inverted; false otherwise.

If the matrix is recognized as the identity or an orthonormal matrix, then this function will quickly invert the matrix using optimized routines.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QMatrix4x4.determinant`, :sip:ref:`~PyQt5.QtGui.QMatrix4x4.normalMatrix`.
