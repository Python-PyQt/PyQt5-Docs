.. sip:method-description::
    :status: todo
    :pysig: c6b57d9cd6760a2cd670e402dfd215a3
    :realsig: (const QRectF&,GLuint,GLenum)
    :digest: 64f287f0f3664d1e5a3e51f2db1383af

This function supports the following use cases:

* On OpenGL and OpenGL ES 1.x it draws the given texture, *textureId*, to the given target rectangle, *target*, in OpenGL model space. The *textureTarget* should be a 2D texture target.

* On OpenGL and OpenGL ES 2.x, if a painter is active, not inside a beginNativePainting / endNativePainting block, and uses the engine with type :sip:ref:`~PyQt5.QtGui.QPaintEngine.Type.OpenGL2`, the function will draw the given texture, *textureId*, to the given target rectangle, *target*, respecting the current painter state. This will let you draw a texture with the clip, transform, render hints, and composition mode set by the painter. Note that the texture target needs to be GL_TEXTURE_2D for this use case, and that this is the only supported use case under OpenGL ES 2.x.
