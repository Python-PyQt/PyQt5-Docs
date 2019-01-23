.. sip:method-description::
    :status: todo
    :pysig: 49c4e82b5e484f0f98053794b701c0e7
    :realsig: (void*)
    :digest: 8a61bc6f4127787d9c9213a7cff1d6e3

Sets the native handle to which the offscreen surface is connected to *handle*.

The native handle will be resolved in the :sip:ref:`~PyQt5.QtGui.QOffscreenSurface.create` function. Calling this function after :sip:ref:`~PyQt5.QtGui.QOffscreenSurface.create` will not re-create a native surface.

**Note:** The interpretation of the native handle is platform specific. Only some platforms will support adopting native handles of offscreen surfaces and platforms that do not implement this support will ignore the handle.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOffscreenSurface.nativeHandle`.
