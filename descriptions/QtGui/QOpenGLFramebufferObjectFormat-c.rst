.. sip:class-description::
    :status: todo
    :brief: Specifies the format of an OpenGL framebuffer object
    :digest: 988bfd51f5c1c7be2dd2e4a5840808f9

The :sip:ref:`~PyQt5.QtGui.QOpenGLFramebufferObjectFormat` class specifies the format of an OpenGL framebuffer object.

A framebuffer object has several characteristics:

* :sip:ref:`~PyQt5.QtGui.QOpenGLFramebufferObjectFormat.setSamples`

* :sip:ref:`~PyQt5.QtGui.QOpenGLFramebufferObjectFormat.setAttachment`

* :sip:ref:`~PyQt5.QtGui.QOpenGLFramebufferObjectFormat.setTextureTarget`

* :sip:ref:`~PyQt5.QtGui.QOpenGLFramebufferObjectFormat.setInternalTextureFormat`

Note that the desired attachments or number of samples per pixels might not be supported by the hardware driver. Call :sip:ref:`~PyQt5.QtGui.QOpenGLFramebufferObject.format` after creating a :sip:ref:`~PyQt5.QtGui.QOpenGLFramebufferObject` to find the exact format that was used to create the frame buffer object.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOpenGLFramebufferObject`.
