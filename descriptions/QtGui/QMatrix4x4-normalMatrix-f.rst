.. sip:method-description::
    :status: todo
    :pysig: 7e18972299727509959d357ad40bf6c9
    :realsig: () const
    :digest: 81caa6cd0c3d9e42d9f0ced6916c7946

Returns the normal matrix corresponding to this 4x4 transformation. The normal matrix is the transpose of the inverse of the top-left 3x3 part of this 4x4 matrix. If the 3x3 sub-matrix is not invertible, this function returns the identity.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QMatrix4x4.inverted`.
