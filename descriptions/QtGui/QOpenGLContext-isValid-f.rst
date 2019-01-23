.. sip:method-description::
    :status: todo
    :pysig: c506ff134babdd6e68ab3e6350e95305
    :realsig: () const
    :digest: 1c09e2aadb0677930d06ead9fa1ee99f

Returns if this context is valid, i.e. has been successfully created.

On some platforms the return value of ``false`` for a context that was successfully created previously indicates that the OpenGL context was lost.

The typical way to handle context loss scenarios in applications is to check via this function whenever :sip:ref:`~PyQt5.QtGui.QOpenGLContext.makeCurrent` fails and returns ``false``. If this function then returns ``false``, recreate the underlying native OpenGL context by calling :sip:ref:`~PyQt5.QtGui.QOpenGLContext.create`, call :sip:ref:`~PyQt5.QtGui.QOpenGLContext.makeCurrent` again and then reinitialize all OpenGL resources.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOpenGLContext.create`.
