.. sip:method-description::
    :status: todo
    :pysig: 394f20baf982feaf490b3a8876afad86
    :realsig: (const char*,const QTransform&)
    :digest: 3c9f076381ce01dba856a6e095274718

This is an overloaded function.

Sets the uniform variable called *name* in the current context to a 3x3 transformation matrix *value* that is specified as a :sip:ref:`~PyQt5.QtGui.QTransform` value.

To set a :sip:ref:`~PyQt5.QtGui.QTransform` value as a 4x4 matrix in a shader, use ``setUniformValue(name, QMatrix4x4(value))``.
