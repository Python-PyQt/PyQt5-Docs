.. sip:method-description::
    :status: todo
    :pysig: 0f9b0ea7a3407ca50e1df7b110b9ad1f
    :realsig: (const QString&)
    :digest: 94b4355c13144dd17855d046f763c2da

This is an overloaded function.

Reads the compressed texture file *fileName* and generates a 2D GL texture from it.

This function can load DirectDrawSurface (DDS) textures in the DXT1, DXT3 and DXT5 DDS formats if the ``GL_ARB_texture_compression`` and ``GL_EXT_texture_compression_s3tc`` extensions are supported.

Since 4.6.1, textures in the ETC1 format can be loaded if the ``GL_OES_compressed_ETC1_RGB8_texture`` extension is supported and the ETC1 texture has been encapsulated in the PVR container format. Also, textures in the PVRTC2 and PVRTC4 formats can be loaded if the ``GL_IMG_texture_compression_pvrtc`` extension is supported.

.. seealso:: :sip:ref:`~PyQt5.QtOpenGL.QGLContext.deleteTexture`.
