.. sip:method-description::
    :status: todo
    :pysig: 728e94b67c057d5c99f22f7ac8f99fb1
    :realsig: (const QPointF&,GLuint,GLenum)
    :digest: bb3969446d44b1098260df8238ca3a28

This function supports the following use cases:

* By default it draws the given texture, *textureId*, at the given *point* in OpenGL model space. The *textureTarget* should be a 2D texture target.

* If a painter is active, not inside a beginNativePainting / endNativePainting block, and uses the engine with type :sip:ref:`~PyQt5.QtGui.QPaintEngine.Type.OpenGL2`, the function will draw the given texture, *textureId*, at the given *point*, respecting the current painter state. This will let you draw a texture with the clip, transform, render hints, and composition mode set by the painter. Note that the texture target needs to be GL_TEXTURE_2D for this use case.

**Note:** This function is not supported under any version of OpenGL ES.
