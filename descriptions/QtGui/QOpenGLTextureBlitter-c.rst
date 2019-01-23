.. sip:class-description::
    :status: todo
    :brief: Convenient way to draw textured quads via OpenGL
    :digest: b6b191b3bdc0c497d9b61198f9c84bf9

The :sip:ref:`~PyQt5.QtGui.QOpenGLTextureBlitter` class provides a convenient way to draw textured quads via OpenGL.

Drawing textured quads, in order to get the contents of a texture onto the screen, is a common operation when developing 2D user interfaces. :sip:ref:`~PyQt5.QtGui.QOpenGLTextureBlitter` provides a convenience class to avoid repeating vertex data, shader sources, buffer and program management and matrix calculations.

For example, a QOpenGLWidget subclass can do the following to draw the contents rendered into a framebuffer at the pixel position ``(x, y)``:

::

    void OpenGLWidget::initializeGL()
    {
        m_blitter.create();
        m_fbo = new QOpenGLFramebufferObject(size);
    }

    void OpenGLWidget::paintGL()
    {
        m_fbo->bind();
        // update offscreen content
        m_fbo->release();

        m_blitter.bind();
        const QRect targetRect(QPoint(x, y), m_fbo->size());
        const QMatrix4x4 target = QOpenGLTextureBlitter::targetTransform(targetRect, QRect(QPoint(0, 0), m_fbo->size()));
        m_blitter.blit(m_fbo->texture(), target, QOpenGLTextureBlitter::OriginBottomLeft);
        m_blitter.release();
    }

The blitter implements GLSL shaders both for GLSL 1.00 (suitable for OpenGL (ES) 2.x and compatibility profiles of newer OpenGL versions) and version 150 (suitable for core profile contexts with OpenGL 3.2 and newer).
