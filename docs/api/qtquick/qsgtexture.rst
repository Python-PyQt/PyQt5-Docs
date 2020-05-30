:orphan:

.. sip:class:: PyQt5.QtQuick.QSGTexture
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtQuick/QSGTexture-c.rst

    .. sip:enum:: PyQt5.QtQuick.QSGTexture.AnisotropyLevel
        :description: QtQuick/QSGTexture-AnisotropyLevel-e.rst

        .. sip:enum-member:: PyQt5.QtQuick.QSGTexture.AnisotropyLevel.Anisotropy16x
            :description: QtQuick/QSGTexture-AnisotropyLevel-Anisotropy16x-v.rst

        .. sip:enum-member:: PyQt5.QtQuick.QSGTexture.AnisotropyLevel.Anisotropy2x
            :description: QtQuick/QSGTexture-AnisotropyLevel-Anisotropy2x-v.rst

        .. sip:enum-member:: PyQt5.QtQuick.QSGTexture.AnisotropyLevel.Anisotropy4x
            :description: QtQuick/QSGTexture-AnisotropyLevel-Anisotropy4x-v.rst

        .. sip:enum-member:: PyQt5.QtQuick.QSGTexture.AnisotropyLevel.Anisotropy8x
            :description: QtQuick/QSGTexture-AnisotropyLevel-Anisotropy8x-v.rst

        .. sip:enum-member:: PyQt5.QtQuick.QSGTexture.AnisotropyLevel.AnisotropyNone
            :description: QtQuick/QSGTexture-AnisotropyLevel-AnisotropyNone-v.rst

    .. sip:enum:: PyQt5.QtQuick.QSGTexture.Filtering
        :description: QtQuick/QSGTexture-Filtering-e.rst

        .. sip:enum-member:: PyQt5.QtQuick.QSGTexture.Filtering.Linear
            :description: QtQuick/QSGTexture-Filtering-Linear-v.rst

        .. sip:enum-member:: PyQt5.QtQuick.QSGTexture.Filtering.Nearest
            :description: QtQuick/QSGTexture-Filtering-Nearest-v.rst

        .. sip:enum-member:: PyQt5.QtQuick.QSGTexture.Filtering.None_
            :description: QtQuick/QSGTexture-Filtering-None_-v.rst

    .. sip:enum:: PyQt5.QtQuick.QSGTexture.WrapMode
        :description: QtQuick/QSGTexture-WrapMode-e.rst

        .. sip:enum-member:: PyQt5.QtQuick.QSGTexture.WrapMode.ClampToEdge
            :description: QtQuick/QSGTexture-WrapMode-ClampToEdge-v.rst

        .. sip:enum-member:: PyQt5.QtQuick.QSGTexture.WrapMode.MirroredRepeat
            :description: QtQuick/QSGTexture-WrapMode-MirroredRepeat-v.rst

        .. sip:enum-member:: PyQt5.QtQuick.QSGTexture.WrapMode.Repeat
            :description: QtQuick/QSGTexture-WrapMode-Repeat-v.rst

    .. sip:method:: PyQt5.QtQuick.QSGTexture.__init__
        :description: QtQuick/QSGTexture-__init__-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGTexture.anisotropyLevel
        :returns:
            :sip:ref:`~PyQt5.QtQuick.QSGTexture.AnisotropyLevel`
        :description: QtQuick/QSGTexture-anisotropyLevel-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGTexture.bind
        :description: QtQuick/QSGTexture-bind-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGTexture.comparisonKey
        :returns:
            int
        :description: QtQuick/QSGTexture-comparisonKey-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGTexture.convertToNormalizedSourceRect
        :args:
            :sip:ref:`~PyQt5.QtCore.QRectF`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRectF`
        :description: QtQuick/QSGTexture-convertToNormalizedSourceRect-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGTexture.filtering
        :returns:
            :sip:ref:`~PyQt5.QtQuick.QSGTexture.Filtering`
        :description: QtQuick/QSGTexture-filtering-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGTexture.hasAlphaChannel
        :returns:
            bool
        :description: QtQuick/QSGTexture-hasAlphaChannel-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGTexture.hasMipmaps
        :returns:
            bool
        :description: QtQuick/QSGTexture-hasMipmaps-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGTexture.horizontalWrapMode
        :returns:
            :sip:ref:`~PyQt5.QtQuick.QSGTexture.WrapMode`
        :description: QtQuick/QSGTexture-horizontalWrapMode-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGTexture.isAtlasTexture
        :returns:
            bool
        :description: QtQuick/QSGTexture-isAtlasTexture-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGTexture.mipmapFiltering
        :returns:
            :sip:ref:`~PyQt5.QtQuick.QSGTexture.Filtering`
        :description: QtQuick/QSGTexture-mipmapFiltering-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGTexture.nativeTexture
        :returns:
            :sip:ref:`~PyQt5.QtQuick.QSGTexture.NativeTexture`
        :description: QtQuick/QSGTexture-nativeTexture-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGTexture.normalizedTextureSubRect
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRectF`
        :description: QtQuick/QSGTexture-normalizedTextureSubRect-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGTexture.removedFromAtlas
        :returns:
            :sip:ref:`~PyQt5.QtQuick.QSGTexture`
        :description: QtQuick/QSGTexture-removedFromAtlas-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGTexture.setAnisotropyLevel
        :args:
            :sip:ref:`~PyQt5.QtQuick.QSGTexture.AnisotropyLevel`
        :description: QtQuick/QSGTexture-setAnisotropyLevel-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGTexture.setFiltering
        :args:
            :sip:ref:`~PyQt5.QtQuick.QSGTexture.Filtering`
        :description: QtQuick/QSGTexture-setFiltering-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGTexture.setHorizontalWrapMode
        :args:
            :sip:ref:`~PyQt5.QtQuick.QSGTexture.WrapMode`
        :description: QtQuick/QSGTexture-setHorizontalWrapMode-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGTexture.setMipmapFiltering
        :args:
            :sip:ref:`~PyQt5.QtQuick.QSGTexture.Filtering`
        :description: QtQuick/QSGTexture-setMipmapFiltering-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGTexture.setVerticalWrapMode
        :args:
            :sip:ref:`~PyQt5.QtQuick.QSGTexture.WrapMode`
        :description: QtQuick/QSGTexture-setVerticalWrapMode-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGTexture.textureId
        :returns:
            int
        :description: QtQuick/QSGTexture-textureId-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGTexture.textureSize
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtQuick/QSGTexture-textureSize-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGTexture.updateBindOptions
        :args:
            force: bool = False
        :description: QtQuick/QSGTexture-updateBindOptions-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGTexture.verticalWrapMode
        :returns:
            :sip:ref:`~PyQt5.QtQuick.QSGTexture.WrapMode`
        :description: QtQuick/QSGTexture-verticalWrapMode-f.rst
