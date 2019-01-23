.. sip:method-description::
    :status: todo
    :pysig: 57e14de0bf851a772cf671e2f54b96a5
    :realsig: (QOpenGLFramebufferObject*,const QRect&,QOpenGLFramebufferObject*,const QRect&,GLbitfield,GLenum,int,int)
    :digest: 18dc33151351d14b459669959532591e

This is an overloaded function.

Convenience overload to blit between two framebuffer objects and to restore the previous framebuffer binding. Equivalent to calling :sip:ref:`~PyQt5.QtGui.QOpenGLFramebufferObject.blitFramebuffer`\ (target, targetRect, source, sourceRect, buffers, filter, readColorAttachmentIndex, drawColorAttachmentIndex, :sip:ref:`~PyQt5.QtGui.QOpenGLFramebufferObject.FramebufferRestorePolicy.RestoreFrameBufferBinding`).
