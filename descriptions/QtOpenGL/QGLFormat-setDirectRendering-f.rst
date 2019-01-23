.. sip:method-description::
    :status: todo
    :pysig: c506ff134babdd6e68ab3e6350e95305
    :realsig: (bool)
    :digest: c36d9d67e8e2462a2405b273ecd54f21

If *enable* is true enables direct rendering; otherwise disables direct rendering.

Direct rendering is enabled by default.

Enabling this option will make OpenGL bypass the underlying window system and render directly from hardware to the screen, if this is supported by the system.

.. seealso:: :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.directRendering`.
