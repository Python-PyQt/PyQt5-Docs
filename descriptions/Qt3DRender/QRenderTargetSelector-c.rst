.. sip:class-description::
    :status: todo
    :brief: Provides a way of specifying a render target
    :realname: Qt3DRender::QRenderTargetSelector
    :digest: e641b104abceab0e20dc70df80c6d679

Provides a way of specifying a render target.

A :sip:ref:`~PyQt5.Qt3DRender.QRenderTargetSelector` is used to select active :sip:ref:`~PyQt5.Qt3DRender.QRenderTarget` for the FrameGraph. When :sip:ref:`~PyQt5.Qt3DRender.QRenderTargetSelector` is present in the FrameGraph, the rendering is directed into QTexture objects or draw buffers instead of the surface specified in the :sip:ref:`~PyQt5.Qt3DRender.QRenderSurfaceSelector`. A render buffer is automatically generated for an attachment point if drawBuffers contain attachment point that any output in the QRenderTarget do not specify. If the drawBuffers is empty, the renderer will default to using all the outputs in QRenderTarget.
