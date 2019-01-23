.. sip:method-description::
    :status: todo
    :pysig: d52f006587cdda3152638509cbc134ee
    :realname: Qt3DRender::QRenderCapture::requestCapture
    :realsig: ()
    :digest: ef8d87fd1ca58ceed3ade18a8bd917a6

Used to request render capture. Only one render capture result is produced per  call even if the frame graph has multiple leaf nodes. The function returns a QRenderCaptureReply object, which receives the captured image when it is done. The user is responsible for deallocating the returned object.
