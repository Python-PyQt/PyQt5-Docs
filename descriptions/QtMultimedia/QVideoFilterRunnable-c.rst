.. sip:class-description::
    :status: todo
    :brief: Represents the implementation of a filter that owns all graphics and computational resources, and performs the actual filtering or calculations
    :digest: e26ac1f75e7a9b2a0c0ec6786e34b32c

The :sip:ref:`~PyQt5.QtMultimedia.QVideoFilterRunnable` class represents the implementation of a filter that owns all graphics and computational resources, and performs the actual filtering or calculations.

Video filters are split into :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoFilter` and corresponding :sip:ref:`~PyQt5.QtMultimedia.QVideoFilterRunnable` instances, similar to QQuickItem and QSGNode. This is necessary to support threaded rendering scenarios. When using the threaded render loop of the Qt Quick scene graph, all rendering happens on a dedicated thread. :sip:ref:`~PyQt5.QtMultimedia.QVideoFilterRunnable` instances always live on this thread and all its functions, :sip:ref:`~PyQt5.QtMultimedia.QVideoFilterRunnable.run`, the constructor, and the destructor, are guaranteed to be invoked on that thread with the OpenGL context bound. :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoFilter` instances live on the main (GUI) thread, like any other :sip:ref:`~PyQt5.QtCore.QObject` and QQuickItem instances created from QML.

Once created, :sip:ref:`~PyQt5.QtMultimedia.QVideoFilterRunnable` instances are managed by Qt Multimedia and will be automatically destroyed and recreated when necessary, for example when the scene graph is invalidated or the QQuickWindow changes or is closed. Creation happens via the :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoFilter.createFilterRunnable` factory function.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoFilter`.
