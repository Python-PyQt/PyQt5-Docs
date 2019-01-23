.. sip:method-description::
    :status: todo
    :pysig: c506ff134babdd6e68ab3e6350e95305
    :realsig: ()
    :digest: bbabc6d44f5814b592ffc612cffe3a6e

Binds the buffer associated with this object to the current OpenGL context. Returns ``false`` if binding was not possible, usually because :sip:ref:`~PyQt5.QtGui.QOpenGLBuffer.type` is not supported on this OpenGL implementation.

The buffer must be bound to the same :sip:ref:`~PyQt5.QtGui.QOpenGLContext` current when :sip:ref:`~PyQt5.QtGui.QOpenGLBuffer.create` was called, or to another :sip:ref:`~PyQt5.QtGui.QOpenGLContext` that is sharing with it. Otherwise, false will be returned from this function.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOpenGLBuffer.release`, :sip:ref:`~PyQt5.QtGui.QOpenGLBuffer.create`.
