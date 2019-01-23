:orphan:

.. sip:class:: PyQt5.QtGui.QOpenGLTextureBlitter
    :description: QtGui/QOpenGLTextureBlitter-c.rst

    .. sip:enum:: PyQt5.QtGui.QOpenGLTextureBlitter.Origin
        :description: QtGui/QOpenGLTextureBlitter-Origin-e.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLTextureBlitter.Origin.OriginBottomLeft
            :description: QtGui/QOpenGLTextureBlitter-Origin-OriginBottomLeft-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLTextureBlitter.Origin.OriginTopLeft
            :description: QtGui/QOpenGLTextureBlitter-Origin-OriginTopLeft-v.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLTextureBlitter.__init__
        :description: QtGui/QOpenGLTextureBlitter-__init__-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLTextureBlitter.bind
        :args:
            target: int = GL_TEXTURE_2D
        :description: QtGui/QOpenGLTextureBlitter-bind-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLTextureBlitter.blit
        :args:
            int
            :sip:ref:`~PyQt5.QtGui.QMatrix4x4`
            :sip:ref:`~PyQt5.QtGui.QOpenGLTextureBlitter.Origin`
        :description: QtGui/QOpenGLTextureBlitter-blit-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLTextureBlitter.blit
        :args:
            int
            :sip:ref:`~PyQt5.QtGui.QMatrix4x4`
            :sip:ref:`~PyQt5.QtGui.QMatrix3x3`
        :description: QtGui/QOpenGLTextureBlitter-blit-f-1.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLTextureBlitter.create
        :returns:
            bool
        :description: QtGui/QOpenGLTextureBlitter-create-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLTextureBlitter.destroy
        :description: QtGui/QOpenGLTextureBlitter-destroy-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLTextureBlitter.isCreated
        :returns:
            bool
        :description: QtGui/QOpenGLTextureBlitter-isCreated-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLTextureBlitter.release
        :description: QtGui/QOpenGLTextureBlitter-release-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLTextureBlitter.setOpacity
        :args:
            float
        :description: QtGui/QOpenGLTextureBlitter-setOpacity-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLTextureBlitter.setRedBlueSwizzle
        :args:
            bool
        :description: QtGui/QOpenGLTextureBlitter-setRedBlueSwizzle-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLTextureBlitter.sourceTransform
        :args:
            :sip:ref:`~PyQt5.QtCore.QRectF`
            :sip:ref:`~PyQt5.QtCore.QSize`
            :sip:ref:`~PyQt5.QtGui.QOpenGLTextureBlitter.Origin`
        :returns:
            :sip:ref:`~PyQt5.QtGui.QMatrix3x3`
        :static:
        :description: QtGui/QOpenGLTextureBlitter-sourceTransform-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLTextureBlitter.supportsExternalOESTarget
        :returns:
            bool
        :description: QtGui/QOpenGLTextureBlitter-supportsExternalOESTarget-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLTextureBlitter.targetTransform
        :args:
            :sip:ref:`~PyQt5.QtCore.QRectF`
            :sip:ref:`~PyQt5.QtCore.QRect`
        :returns:
            :sip:ref:`~PyQt5.QtGui.QMatrix4x4`
        :static:
        :description: QtGui/QOpenGLTextureBlitter-targetTransform-f.rst
