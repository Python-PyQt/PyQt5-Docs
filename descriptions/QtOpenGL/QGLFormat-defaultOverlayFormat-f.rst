.. sip:method-description::
    :status: todo
    :pysig: df1cdba42ded00101db045e2b92d4144
    :realsig: ()
    :digest: 89edf688b1adba13aff48c1465ae243b

Returns the default :sip:ref:`~PyQt5.QtOpenGL.QGLFormat` for overlay contexts.

The default overlay format is:

* :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.setDoubleBuffer` Disabled.

* :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.setDepth` Disabled.

* :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.setRgba` Disabled (i.e., color index enabled).

* :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.setAlpha` Disabled.

* :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.setAccum` Disabled.

* :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.setStencil` Disabled.

* :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.setStereo` Disabled.

* :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.setDirectRendering` Enabled.

* :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.setOverlay` Disabled.

* :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.setSampleBuffers` Disabled.

* :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.setPlane` 1 (i.e., first overlay plane).

.. seealso:: :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.setDefaultOverlayFormat`, :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.setDefaultFormat`.
