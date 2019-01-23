.. sip:method-description::
    :status: todo
    :pysig: ed36a1ef76a59ee3f15180e0441188ad
    :realsig: (const QVariant&)
    :digest: ca859d4b44e14995bc3d00518eb31945

Set the native handles for this context. When :sip:ref:`~PyQt5.QtGui.QOpenGLContext.create` is called and a native handle is set, configuration settings, like :sip:ref:`~PyQt5.QtGui.QOpenGLContext.format`, are ignored since this :sip:ref:`~PyQt5.QtGui.QOpenGLContext` will wrap an already created native context instead of creating a new one from scratch.

On some platforms the native context handle is not sufficient and other related handles (for example, for a window or display) have to be provided in addition. Therefore *handle* is variant containing a platform-specific value type. These classes can be found in the QtPlatformHeaders module.

When :sip:ref:`~PyQt5.QtGui.QOpenGLContext.create` is called with native handles set, :sip:ref:`~PyQt5.QtGui.QOpenGLContext` does not take ownership of the handles, so destroying the :sip:ref:`~PyQt5.QtGui.QOpenGLContext` does not destroy the native context.

**Note:** Some frameworks track the current context and surfaces internally. Making the adopted :sip:ref:`~PyQt5.QtGui.QOpenGLContext` current via Qt will have no effect on such other frameworks' internal state. Therefore a subsequent :sip:ref:`~PyQt5.QtGui.QOpenGLContext.makeCurrent` done via the other framework may have no effect. It is therefore advisable to make explicit calls to make no context and surface current to reset the other frameworks' internal state after performing OpenGL operations via Qt.

**Note:** Using foreign contexts with Qt windows and Qt contexts with windows and surfaces created by other frameworks may give unexpected results, depending on the platform, due to potential mismatches in context and window pixel formats. To make sure this does not happen, avoid making contexts and surfaces from different frameworks current together. Instead, prefer approaches based on context sharing where OpenGL resources like textures are accessible both from Qt's and the foreign framework's contexts.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOpenGLContext.nativeHandle`.
