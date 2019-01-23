:orphan:

.. sip:class:: PyQt5.QtQuick.QSGEngine
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtQuick/QSGEngine-c.rst

    .. sip:enum:: PyQt5.QtQuick.QSGEngine.CreateTextureOption
        :description: QtQuick/QSGEngine-CreateTextureOption-e.rst

        .. sip:enum-member:: PyQt5.QtQuick.QSGEngine.CreateTextureOption.TextureCanUseAtlas
            :description: QtQuick/QSGEngine-CreateTextureOption-TextureCanUseAtlas-v.rst

        .. sip:enum-member:: PyQt5.QtQuick.QSGEngine.CreateTextureOption.TextureHasAlphaChannel
            :description: QtQuick/QSGEngine-CreateTextureOption-TextureHasAlphaChannel-v.rst

        .. sip:enum-member:: PyQt5.QtQuick.QSGEngine.CreateTextureOption.TextureIsOpaque
            :description: QtQuick/QSGEngine-CreateTextureOption-TextureIsOpaque-v.rst

        .. sip:enum-member:: PyQt5.QtQuick.QSGEngine.CreateTextureOption.TextureOwnsGLTexture
            :description: QtQuick/QSGEngine-CreateTextureOption-TextureOwnsGLTexture-v.rst

    .. sip:method:: PyQt5.QtQuick.QSGEngine.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtQuick/QSGEngine-__init__-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGEngine.createImageNode
        :returns:
            :sip:ref:`~PyQt5.QtQuick.QSGImageNode`
        :description: QtQuick/QSGEngine-createImageNode-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGEngine.createRectangleNode
        :returns:
            :sip:ref:`~PyQt5.QtQuick.QSGRectangleNode`
        :description: QtQuick/QSGEngine-createRectangleNode-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGEngine.createRenderer
        :returns:
            :sip:ref:`~PyQt5.QtQuick.QSGAbstractRenderer`
        :description: QtQuick/QSGEngine-createRenderer-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGEngine.createTextureFromId
        :args:
            int
            :sip:ref:`~PyQt5.QtCore.QSize`
            options: Union[:sip:ref:`~PyQt5.QtQuick.QSGEngine.CreateTextureOptions`, :sip:ref:`~PyQt5.QtQuick.QSGEngine.CreateTextureOption`] = QSGEngine.CreateTextureOption()
        :returns:
            :sip:ref:`~PyQt5.QtQuick.QSGTexture`
        :description: QtQuick/QSGEngine-createTextureFromId-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGEngine.createTextureFromImage
        :args:
            :sip:ref:`~PyQt5.QtGui.QImage`
            options: Union[:sip:ref:`~PyQt5.QtQuick.QSGEngine.CreateTextureOptions`, :sip:ref:`~PyQt5.QtQuick.QSGEngine.CreateTextureOption`] = QSGEngine.CreateTextureOption()
        :returns:
            :sip:ref:`~PyQt5.QtQuick.QSGTexture`
        :description: QtQuick/QSGEngine-createTextureFromImage-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGEngine.initialize
        :args:
            :sip:ref:`~PyQt5.QtGui.QOpenGLContext`
        :description: QtQuick/QSGEngine-initialize-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGEngine.invalidate
        :description: QtQuick/QSGEngine-invalidate-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGEngine.rendererInterface
        :returns:
            :sip:ref:`~PyQt5.QtQuick.QSGRendererInterface`
        :description: QtQuick/QSGEngine-rendererInterface-f.rst
