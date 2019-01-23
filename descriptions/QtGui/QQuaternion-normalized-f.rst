.. sip:method-description::
    :status: todo
    :pysig: 288ce3b30b9c2f86e51bc6371c191487
    :realsig: () const
    :digest: 55df5dd951d247853d62b57265d215ac

Returns the normalized unit form of this quaternion.

If this quaternion is null, then a null quaternion is returned. If the length of the quaternion is very close to 1, then the quaternion will be returned as-is. Otherwise the normalized form of the quaternion of length 1 will be returned.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QQuaternion.normalize`, :sip:ref:`~PyQt5.QtGui.QQuaternion.length`.
