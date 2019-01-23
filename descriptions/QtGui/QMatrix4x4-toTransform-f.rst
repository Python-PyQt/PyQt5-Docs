.. sip:method-description::
    :status: todo
    :pysig: 46adf10cdda9e344626baf7eaf9aa4fc
    :realsig: () const
    :digest: ad09f6e6fe70d5bbdf4203d8f11533a6

Returns the conventional Qt 2D transformation matrix that corresponds to this matrix.

The returned :sip:ref:`~PyQt5.QtGui.QTransform` is formed by simply dropping the third row and third column of the :sip:ref:`~PyQt5.QtGui.QMatrix4x4`. This is suitable for implementing orthographic projections where the z co-ordinate should be dropped rather than projected.

.. seealso:: toAffine().
