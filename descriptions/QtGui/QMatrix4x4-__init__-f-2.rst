.. sip:method-description::
    :status: todo
    :pysig: 46adf10cdda9e344626baf7eaf9aa4fc
    :realsig: (const QTransform&)
    :digest: 58eb7796b26984394ced5f7c8e22d5dd

Constructs a 4x4 matrix from the conventional Qt 2D transformation matrix *transform*.

If *transform* has a special type (identity, translate, scale, etc), the programmer should follow this constructor with a call to :sip:ref:`~PyQt5.QtGui.QMatrix4x4.optimize` if they wish :sip:ref:`~PyQt5.QtGui.QMatrix4x4` to optimize further calls to :sip:ref:`~PyQt5.QtGui.QMatrix4x4.translate`, :sip:ref:`~PyQt5.QtGui.QMatrix4x4.scale`, etc.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QMatrix4x4.toTransform`, :sip:ref:`~PyQt5.QtGui.QMatrix4x4.optimize`.
