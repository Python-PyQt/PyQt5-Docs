.. sip:method-description::
    :status: todo
    :pysig: d8cf237f98363e87feeab68359d9f5d3
    :realsig: (const QColor&) const
    :digest: 6fe9117a2faede409f1b0815afa4647e

Convenience function for specifying a drawing color to OpenGL. Calls glColor4 (in RGBA mode) or glIndex (in color-index mode) with the color *c*. Applies to this widgets GL context.

**Note:** This function is not supported on OpenGL/ES 2.0 systems.

.. seealso:: :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.qglClearColor`, :sip:ref:`~PyQt5.QtOpenGL.QGLContext.currentContext`, :sip:ref:`~PyQt5.QtGui.QColor`.
