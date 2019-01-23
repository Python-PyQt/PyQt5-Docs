.. sip:method-description::
    :status: todo
    :pysig: 17477b5635be1240912a9f4e714dd5c9
    :realsig: (QSurface*)
    :digest: b2de92f5ce9a5ebd471e9da6e64c421a

Makes the context current in the current thread, against the given *surface*. Returns ``true`` if successful; otherwise returns ``false``. The latter may happen if the surface is not exposed, or the graphics hardware is not available due to e.g. the application being suspended.

If *surface* is 0 this is equivalent to calling :sip:ref:`~PyQt5.QtGui.QOpenGLContext.doneCurrent`.

Avoid calling this function from a different thread than the one the :sip:ref:`~PyQt5.QtGui.QOpenGLContext` instance lives in. If you wish to use :sip:ref:`~PyQt5.QtGui.QOpenGLContext` from a different thread you should first make sure it's not current in the current thread, by calling :sip:ref:`~PyQt5.QtGui.QOpenGLContext.doneCurrent` if necessary. Then call moveToThread(otherThread) before using it in the other thread.

By default Qt employs a check that enforces the above condition on the thread affinity. It is still possible to disable this check by setting the ``Qt::AA_DontCheckOpenGLContextThreadAffinity`` application attribute. Be sure to understand the consequences of using QObjects from outside the thread they live in, as explained in the QObject thread affinity documentation.

.. seealso:: functions(), :sip:ref:`~PyQt5.QtGui.QOpenGLContext.doneCurrent`.
