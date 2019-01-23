.. sip:method-description::
    :status: todo
    :pysig: 15249dfca430e723f3ec543d979999ee
    :realsig: (QOpenGLShader::ShaderType,QOpenGLContext*)
    :digest: e788a3a14910b3cdfc4e906c09f60921

Returns ``true`` if shader programs of type *type* are supported on this system; false otherwise.

The *context* is used to resolve the GLSL extensions. If *context* is null, then :sip:ref:`~PyQt5.QtGui.QOpenGLContext.currentContext` is used.
