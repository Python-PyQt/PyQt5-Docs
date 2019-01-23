.. sip:method-description::
    :status: todo
    :pysig: 9092193d9c26986ae140ccb2f8d487c1
    :realname: Qt3DRender::QRenderCapture::requestCapture
    :realsig: (const QRect&)
    :digest: 0c25ca005015b745135c2cdbce39e19f

Used to request render capture from a specified *rect*. Only one render capture result is produced per :sip:ref:`~PyQt5.Qt3DRender.QRenderCapture.requestCapture` call even if the frame graph has multiple leaf nodes. The function returns a QRenderCaptureReply object, which receives the captured image when it is done. The user is responsible for deallocating the returned object.
