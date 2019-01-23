.. sip:class-description::
    :status: todo
    :brief: Drawing area for QWindow
    :digest: 550ac76b62d89b0f9449f76b41c608c9

The :sip:ref:`~PyQt5.QtGui.QBackingStore` class provides a drawing area for :sip:ref:`~PyQt5.QtGui.QWindow`.

:sip:ref:`~PyQt5.QtGui.QBackingStore` enables the use of :sip:ref:`~PyQt5.QtGui.QPainter` to paint on a :sip:ref:`~PyQt5.QtGui.QWindow` with type RasterSurface. The other way of rendering to a :sip:ref:`~PyQt5.QtGui.QWindow` is through the use of OpenGL with :sip:ref:`~PyQt5.QtGui.QOpenGLContext`.

A :sip:ref:`~PyQt5.QtGui.QBackingStore` contains a buffered representation of the window contents, and thus supports partial updates by using :sip:ref:`~PyQt5.QtGui.QPainter` to only update a sub region of the window contents.

:sip:ref:`~PyQt5.QtGui.QBackingStore` might be used by an application that wants to use :sip:ref:`~PyQt5.QtGui.QPainter` without OpenGL acceleration and without the extra overhead of using the :sip:ref:`~PyQt5.QtWidgets.QWidget` or QGraphicsView UI stacks. For an example of how to use :sip:ref:`~PyQt5.QtGui.QBackingStore` see the `Raster Window Example <https://doc.qt.io/qt-5/qtgui-rasterwindow-example.html>`_.
