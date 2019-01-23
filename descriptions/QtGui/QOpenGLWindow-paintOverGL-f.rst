.. sip:method-description::
    :status: todo
    :pysig: d41d8cd98f00b204e9800998ecf8427e
    :realsig: ()
    :digest: 6c69018c733f392631b25d2bb486426b

This virtual function is called after each invocation of :sip:ref:`~PyQt5.QtGui.QOpenGLWindow.paintGL`.

When the update mode is set to :sip:ref:`~PyQt5.QtGui.QOpenGLWindow.UpdateBehavior.NoPartialUpdate`, there is no difference between this function and :sip:ref:`~PyQt5.QtGui.QOpenGLWindow.paintGL`, performing rendering in either of them leads to the same result.

Like :sip:ref:`~PyQt5.QtGui.QOpenGLWindow.paintUnderGL`, rendering in this function targets the default framebuffer of the window, regardless of the update behavior. It gets called after :sip:ref:`~PyQt5.QtGui.QOpenGLWindow.paintGL` has returned and the blit (\ :sip:ref:`~PyQt5.QtGui.QOpenGLWindow.UpdateBehavior.PartialUpdateBlit`) or quad drawing (\ :sip:ref:`~PyQt5.QtGui.QOpenGLWindow.UpdateBehavior.PartialUpdateBlend`) has been done.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOpenGLWindow.paintGL`, :sip:ref:`~PyQt5.QtGui.QOpenGLWindow.paintUnderGL`, :sip:ref:`~PyQt5.QtGui.QOpenGLWindow.UpdateBehavior.UpdateBehavior`.
