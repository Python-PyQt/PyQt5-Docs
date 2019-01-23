.. sip:method-description::
    :status: todo
    :pysig: ed36a1ef76a59ee3f15180e0441188ad
    :realsig: () const
    :digest: 34a339077277e04a2939069458bdf6f8

Returns the native handle for the context.

This function provides access to the :sip:ref:`~PyQt5.QtGui.QOpenGLContext`'s underlying native context. The returned variant contains a platform-specific value type. These classes can be found in the module QtPlatformHeaders.

On platforms where retrieving the native handle is not supported, or if neither :sip:ref:`~PyQt5.QtGui.QOpenGLContext.create` nor :sip:ref:`~PyQt5.QtGui.QOpenGLContext.setNativeHandle` was called, a null variant is returned.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOpenGLContext.setNativeHandle`.
