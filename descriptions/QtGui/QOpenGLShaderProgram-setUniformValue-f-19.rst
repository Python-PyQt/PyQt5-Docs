.. sip:method-description::
    :status: todo
    :pysig: c965dd0afeff845fbf9f7047f73bccac
    :realsig: (int,const QTransform&)
    :digest: 7b6cadf1d29c64dcb7186ffdae5d70c7

Sets the uniform variable at *location* in the current context to a 3x3 transformation matrix *value* that is specified as a :sip:ref:`~PyQt5.QtGui.QTransform` value.

To set a :sip:ref:`~PyQt5.QtGui.QTransform` value as a 4x4 matrix in a shader, use ``setUniformValue(location, QMatrix4x4(value))``.
