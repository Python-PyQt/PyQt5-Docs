.. sip:class-description::
    :status: todo
    :brief: Abstract definition of how QPainter draws to a given device on a given platform
    :digest: 609790057852f7a6a543e9fcfcc637a9

The :sip:ref:`~PyQt5.QtGui.QPaintEngine` class provides an abstract definition of how :sip:ref:`~PyQt5.QtGui.QPainter` draws to a given device on a given platform.

Qt provides several premade implementations of :sip:ref:`~PyQt5.QtGui.QPaintEngine` for the different painter backends we support. The primary paint engine provided is the raster paint engine, which contains a software rasterizer which supports the full feature set on all supported platforms. This is the default for painting on :sip:ref:`~PyQt5.QtWidgets.QWidget`-based classes in e.g. on Windows, X11 and `macOS <https://doc.qt.io/qt-5/qtwebengine-platform-notes.html#macos>`_, it is the backend for painting on :sip:ref:`~PyQt5.QtGui.QImage` and it is used as a fallback for paint engines that do not support a certain capability. In addition we provide :sip:ref:`~PyQt5.QtGui.QPaintEngine` implementations for :sip:ref:`~PyQt5.QtGui.QPaintEngine.Type.OpenGL` (accessible through :sip:ref:`~PyQt5.QtOpenGL.QGLWidget`) and printing (which allows using :sip:ref:`~PyQt5.QtGui.QPainter` to draw on a QPrinter object).

If one wants to use :sip:ref:`~PyQt5.QtGui.QPainter` to draw to a different backend, one must subclass :sip:ref:`~PyQt5.QtGui.QPaintEngine` and reimplement all its virtual functions. The :sip:ref:`~PyQt5.QtGui.QPaintEngine` implementation is then made available by subclassing :sip:ref:`~PyQt5.QtGui.QPaintDevice` and reimplementing the virtual function :sip:ref:`~PyQt5.QtGui.QPaintDevice.paintEngine`.

:sip:ref:`~PyQt5.QtGui.QPaintEngine` is created and owned by the :sip:ref:`~PyQt5.QtGui.QPaintDevice` that created it.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPainter`, :sip:ref:`~PyQt5.QtGui.QPaintDevice.paintEngine`, `Paint System <https://doc.qt.io/qt-5/paintsystem.html>`_.
