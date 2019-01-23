.. sip:method-description::
    :status: todo
    :pysig: 450ebbb91b1af08ea33413e61783410f
    :realsig: ()
    :digest: ee22c95716bf2ae0b0a3228a1af07369

Returns a copy of the framebuffer.

**Note:** This is a potentially expensive operation because it relies on glReadPixels() to read back the pixels. This may be slow and can stall the GPU pipeline.

**Note:** When used together with update behavior ``NoPartialUpdate``, the returned image may not contain the desired content when called after the front and back buffers have been swapped (unless preserved swap is enabled in the underlying windowing system interface). In this mode the function reads from the back buffer and the contents of that may not match the content on the screen (the front buffer). In this case the only place where this function can safely be used is :sip:ref:`~PyQt5.QtGui.QOpenGLWindow.paintGL` or :sip:ref:`~PyQt5.QtGui.QOpenGLWindow.paintOverGL`.
