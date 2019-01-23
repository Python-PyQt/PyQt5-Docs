.. sip:method-description::
    :status: todo
    :pysig: 46adf10cdda9e344626baf7eaf9aa4fc
    :realsig: () const
    :digest: 7375d668f7933c2d2a41748586ab63d4

Returns the matrix that transforms from logical coordinates to device coordinates of the platform dependent paint device.

This function is *only* needed when using platform painting commands on the platform dependent handle (Qt::HANDLE), and the platform does not do transformations nativly.

The :sip:ref:`~PyQt5.QtGui.QPaintEngine.PaintEngineFeature` enum can be queried to determine whether the platform performs the transformations or not.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPainter.worldTransform`, :sip:ref:`~PyQt5.QtGui.QPaintEngine.hasFeature`.
