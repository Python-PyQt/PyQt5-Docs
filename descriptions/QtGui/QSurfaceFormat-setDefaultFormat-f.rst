.. sip:method-description::
    :status: todo
    :pysig: 3e33a867cfd7af36f9f3817f1d5a3267
    :realsig: (const QSurfaceFormat&)
    :digest: bc3b8faef9c73359e0fce4bc767ada71

Sets the global default surface *format*.

This format is used by default in :sip:ref:`~PyQt5.QtGui.QOpenGLContext`, :sip:ref:`~PyQt5.QtGui.QWindow`, QOpenGLWidget and similar classes.

It can always be overridden on a per-instance basis by using the class in question's own setFormat() function. However, it is often more convenient to set the format for all windows once at the start of the application. It also guarantees proper behavior in cases where shared contexts are required, because settings the format via this function guarantees that all contexts and surfaces, even the ones created internally by Qt, will use the same format.

**Note:** When setting Qt::AA_ShareOpenGLContexts, it is strongly recommended to place the call to this function before the construction of the :sip:ref:`~PyQt5.QtGui.QGuiApplication` or QApplication. Otherwise *format* will not be applied to the global share context and therefore issues may arise with context sharing afterwards.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QSurfaceFormat.defaultFormat`.
