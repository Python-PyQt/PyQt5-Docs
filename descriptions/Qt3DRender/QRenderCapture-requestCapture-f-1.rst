.. sip:method-description::
    :status: todo
    :pysig: c935228a6803d0eedeb993281b5b2345
    :realname: Qt3DRender::QRenderCapture::requestCapture
    :realsig: (int)
    :digest: ac729dcbfc2f079d7c4109aadb894531

Used to request render capture. User can specify a *captureId* to identify the request. The requestId does not have to be unique. Only one render capture result is produced per :sip:ref:`~PyQt5.Qt3DRender.QRenderCapture.requestCapture` call even if the frame graph has multiple leaf nodes. The function returns a QRenderCaptureReply object, which receives the captured image when it is done. The user is responsible for deallocating the returned object.
