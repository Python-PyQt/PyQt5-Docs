.. sip:enum-member-description::
    :status: todo
    :value: 0x0008
    :digest: 4db749e971836fb5d6647ab685f7ff62

Enables notifications about resets of the OpenGL context. The status is then queryable via the context's :sip:ref:`~PyQt5.QtGui.QOpenGLContext.isValid` function. Note that not setting this flag does not guarantee that context state loss never occurs. Additionally, some implementations may choose to report context loss regardless of this flag.
