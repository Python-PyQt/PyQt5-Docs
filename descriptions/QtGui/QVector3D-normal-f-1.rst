.. sip:method-description::
    :status: todo
    :pysig: 52a397b16037a95bb055b014c7fbb7a0
    :realsig: (const QVector3D&,const QVector3D&,const QVector3D&)
    :digest: f54740a12578c77f33f7bcaa47151d6d

This is an overloaded function.

Returns the normal vector of a plane defined by vectors *v2* - *v1* and *v3* - *v1*, normalized to be a unit vector.

Use :sip:ref:`~PyQt5.QtGui.QVector3D.crossProduct` to compute the cross-product of *v2* - *v1* and *v3* - *v1* if you do not need the result to be normalized to a unit vector.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QVector3D.crossProduct`, :sip:ref:`~PyQt5.QtGui.QVector3D.distanceToPlane`.
