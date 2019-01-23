.. sip:method-description::
    :status: todo
    :pysig: d1f08cba644f255f7336155c39e90a4c
    :realsig: (const QVector3D&,const QVector3D&)
    :digest: 12fc9c3e4e28a855b7e9344b120c58a3

Returns the normal vector of a plane defined by vectors *v1* and *v2*, normalized to be a unit vector.

Use :sip:ref:`~PyQt5.QtGui.QVector3D.crossProduct` to compute the cross-product of *v1* and *v2* if you do not need the result to be normalized to a unit vector.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QVector3D.crossProduct`, :sip:ref:`~PyQt5.QtGui.QVector3D.distanceToPlane`.
