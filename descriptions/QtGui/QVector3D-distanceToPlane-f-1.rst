.. sip:method-description::
    :status: todo
    :pysig: ab0de481d64870d04ec16b5f67e0cfb2
    :realsig: (const QVector3D&,const QVector3D&,const QVector3D&) const
    :digest: f5eb4519576b39748e57e58f13f10454

This is an overloaded function.

Returns the distance from this vertex a plane defined by the vertices *plane1*, *plane2* and *plane3*.

The return value will be negative if the vertex is below the plane, or zero if it is on the plane.

The two vectors that define the plane are *plane2* - *plane1* and *plane3* - *plane1*.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QVector3D.normal`, :sip:ref:`~PyQt5.QtGui.QVector3D.distanceToLine`.
