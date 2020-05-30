:orphan:

.. sip:class:: PyQt5.QtQuick.QSGMaterialRhiShader
    :inherits: :sip:ref:`~PyQt5.QtQuick.QSGMaterialShader`
    :description: QtQuick/QSGMaterialRhiShader-c.rst

    .. sip:enum:: PyQt5.QtQuick.QSGMaterialRhiShader.Flag
        :description: QtQuick/QSGMaterialRhiShader-Flag-e.rst

        .. sip:enum-member:: PyQt5.QtQuick.QSGMaterialRhiShader.Flag.UpdatesGraphicsPipelineState
            :description: QtQuick/QSGMaterialRhiShader-Flag-UpdatesGraphicsPipelineState-v.rst

    .. sip:method:: PyQt5.QtQuick.QSGMaterialRhiShader.__init__
        :description: QtQuick/QSGMaterialRhiShader-__init__-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGMaterialRhiShader.flags
        :returns:
            :sip:ref:`~PyQt5.QtQuick.QSGMaterialRhiShader.Flags`
        :description: QtQuick/QSGMaterialRhiShader-flags-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGMaterialRhiShader.setFlag
        :args:
            Union[:sip:ref:`~PyQt5.QtQuick.QSGMaterialRhiShader.Flags`, :sip:ref:`~PyQt5.QtQuick.QSGMaterialRhiShader.Flag`]
            on: bool = True
        :description: QtQuick/QSGMaterialRhiShader-setFlag-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGMaterialRhiShader.updateGraphicsPipelineState
        :args:
            :sip:ref:`~PyQt5.QtQuick.QSGMaterialRhiShader.RenderState`
            :sip:ref:`~PyQt5.QtQuick.QSGMaterialRhiShader.GraphicsPipelineState`
            :sip:ref:`~PyQt5.QtQuick.QSGMaterial`
            :sip:ref:`~PyQt5.QtQuick.QSGMaterial`
        :returns:
            bool
        :description: QtQuick/QSGMaterialRhiShader-updateGraphicsPipelineState-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGMaterialRhiShader.updateSampledImage
        :args:
            :sip:ref:`~PyQt5.QtQuick.QSGMaterialRhiShader.RenderState`
            int
            :sip:ref:`~PyQt5.QtQuick.QSGMaterial`
            :sip:ref:`~PyQt5.QtQuick.QSGMaterial`
        :returns:
            :sip:ref:`~PyQt5.QtQuick.QSGTexture`
        :description: QtQuick/QSGMaterialRhiShader-updateSampledImage-f.rst

    .. sip:method:: PyQt5.QtQuick.QSGMaterialRhiShader.updateUniformData
        :args:
            :sip:ref:`~PyQt5.QtQuick.QSGMaterialRhiShader.RenderState`
            :sip:ref:`~PyQt5.QtQuick.QSGMaterial`
            :sip:ref:`~PyQt5.QtQuick.QSGMaterial`
        :returns:
            bool
        :description: QtQuick/QSGMaterialRhiShader-updateUniformData-f.rst
