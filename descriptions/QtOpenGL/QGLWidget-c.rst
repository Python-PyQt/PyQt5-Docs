.. sip:class-description::
    :status: todo
    :brief: Widget for rendering OpenGL graphics
    :digest: 56779704d095ef5ce1b2b43087bcc7d7

The :sip:ref:`~PyQt5.QtOpenGL.QGLWidget` class is a widget for rendering OpenGL graphics.

:sip:ref:`~PyQt5.QtOpenGL.QGLWidget` provides functionality for displaying OpenGL graphics integrated into a Qt application. It is very simple to use. You inherit from it and use the subclass like any other :sip:ref:`~PyQt5.QtWidgets.QWidget`, except that you have the choice between using :sip:ref:`~PyQt5.QtGui.QPainter` and standard OpenGL rendering commands.

**Note:** This class is part of the legacy `Qt OpenGL <https://doc.qt.io/qt-5/qtopengl-index.html>`_ module and, like the other ``QGL`` classes, should be avoided in the new applications. Instead, starting from Qt 5.4, prefer using QOpenGLWidget and the ``QOpenGL`` classes.

:sip:ref:`~PyQt5.QtOpenGL.QGLWidget` provides three convenient virtual functions that you can reimplement in your subclass to perform the typical OpenGL tasks:

* :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.paintGL` - Renders the OpenGL scene. Gets called whenever the widget needs to be updated.

* :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.resizeGL` - Sets up the OpenGL viewport, projection, etc. Gets called whenever the widget has been resized (and also when it is shown for the first time because all newly created widgets get a resize event automatically).

* :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.initializeGL` - Sets up the OpenGL rendering context, defines display lists, etc. Gets called once before the first time :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.resizeGL` or :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.paintGL` is called.

Here is a rough outline of how a :sip:ref:`~PyQt5.QtOpenGL.QGLWidget` subclass might look:

.. literalinclude:: ../../../snippets/qtbase-src-opengl-doc-snippets-code-src_opengl_qgl.py
    :lines: 141-183

If you need to trigger a repaint from places other than :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.paintGL` (a typical example is when using :sip:ref:`~PyQt5.QtCore.QTimer` to animate scenes), you should call the widget's :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.updateGL` function.

Your widget's OpenGL rendering context is made current when :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.paintGL`, :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.resizeGL`, or :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.initializeGL` is called. If you need to call the standard OpenGL API functions from other places (e.g. in your widget's constructor or in your own paint functions), you must call :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.makeCurrent` first.

:sip:ref:`~PyQt5.QtOpenGL.QGLWidget` provides functions for requesting a new display :sip:ref:`~PyQt5.QtOpenGL.QGLFormat` and you can also create widgets with customized rendering :sip:ref:`~PyQt5.QtOpenGL.QGLContext`.

You can also share OpenGL display lists between :sip:ref:`~PyQt5.QtOpenGL.QGLWidget` objects (see the documentation of the :sip:ref:`~PyQt5.QtOpenGL.QGLWidget` constructors for details).

Note that under Windows, the :sip:ref:`~PyQt5.QtOpenGL.QGLContext` belonging to a :sip:ref:`~PyQt5.QtOpenGL.QGLWidget` has to be recreated when the :sip:ref:`~PyQt5.QtOpenGL.QGLWidget` is reparented. This is necessary due to limitations on the Windows platform. This will most likely cause problems for users that have subclassed and installed their own :sip:ref:`~PyQt5.QtOpenGL.QGLContext` on a :sip:ref:`~PyQt5.QtOpenGL.QGLWidget`. It is possible to work around this issue by putting the :sip:ref:`~PyQt5.QtOpenGL.QGLWidget` inside a dummy widget and then reparenting the dummy widget, instead of the :sip:ref:`~PyQt5.QtOpenGL.QGLWidget`. This will side-step the issue altogether, and is what we recommend for users that need this kind of functionality.

On `macOS <https://doc.qt.io/qt-5/qtwebengine-platform-notes.html#macos>`_, when Qt is built with Cocoa support, a :sip:ref:`~PyQt5.QtOpenGL.QGLWidget` can't have any sibling widgets placed ontop of itself. This is due to limitations in the Cocoa API and is not supported by Apple.

.. _qglwidget-overlays:

Overlays
--------

The :sip:ref:`~PyQt5.QtOpenGL.QGLWidget` creates a GL overlay context in addition to the normal context if overlays are supported by the underlying system.

If you want to use overlays, you specify it in the :sip:ref:`~PyQt5.QtOpenGL.QGLFormat`. (Note: Overlay must be requested in the format passed to the :sip:ref:`~PyQt5.QtOpenGL.QGLWidget` constructor.) Your GL widget should also implement some or all of these virtual methods:

* :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.paintOverlayGL`

* :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.resizeOverlayGL`

* :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.initializeOverlayGL`

These methods work in the same way as the normal :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.paintGL` etc. functions, except that they will be called when the overlay context is made current. You can explicitly make the overlay context current by using :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.makeOverlayCurrent`, and you can access the overlay context directly (e.g. to ask for its transparent color) by calling :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.overlayContext`.

On X servers in which the default visual is in an overlay plane, non-GL Qt windows can also be used for overlays.

.. _qglwidget-painting-techniques:

Painting Techniques
-------------------

As described above, subclass :sip:ref:`~PyQt5.QtOpenGL.QGLWidget` to render pure 3D content in the following way:

* Reimplement the :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.initializeGL` and :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.resizeGL` to set up the OpenGL state and provide a perspective transformation.

* Reimplement :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.paintGL` to paint the 3D scene, calling only OpenGL functions to draw on the widget.

It is also possible to draw 2D graphics onto a :sip:ref:`~PyQt5.QtOpenGL.QGLWidget` subclass, it is necessary to reimplement :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.paintEvent` and do the following:

* Construct a :sip:ref:`~PyQt5.QtGui.QPainter` object.

* Initialize it for use on the widget with the :sip:ref:`~PyQt5.QtGui.QPainter.begin` function.

* Draw primitives using :sip:ref:`~PyQt5.QtGui.QPainter`'s member functions.

* Call :sip:ref:`~PyQt5.QtGui.QPainter.end` to finish painting.

.. _qglwidget-threading:

Threading
---------

As of Qt version 4.8, support for doing threaded GL rendering has been improved. There are three scenarios that we currently support:

* 1. Buffer swapping in a thread.

  Swapping buffers in a double buffered context may be a synchronous, locking call that may be a costly operation in some GL implementations. Especially so on embedded devices. It's not optimal to have the CPU idling while the GPU is doing a buffer swap. In those cases it is possible to do the rendering in the main thread and do the actual buffer swap in a separate thread. This can be done with the following steps:

  1. Call :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.doneCurrent` in the main thread when the rendering is finished.

  2. Call QGLContext::moveToThread(swapThread) to transfer ownership of the context to the swapping thread.

  3. Notify the swapping thread that it can grab the context.

  4. Make the rendering context current in the swapping thread with :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.makeCurrent` and then call :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.swapBuffers`.

  5. Call :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.doneCurrent` in the swapping thread.

  6. Call QGLContext::moveToThread(\ :sip:ref:`~PyQt5.QtWidgets.qApp`->thread()) and notify the main thread that swapping is done.

  Doing this will free up the main thread so that it can continue with, for example, handling UI events or network requests. Even if there is a context swap involved, it may be preferable compared to having the main thread wait while the GPU finishes the swap operation. Note that this is highly implementation dependent.

* 2. Texture uploading in a thread.

  Doing texture uploads in a thread may be very useful for applications handling large amounts of images that needs to be displayed, like for instance a photo gallery application. This is supported in Qt through the existing :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.bindTexture` API. A simple way of doing this is to create two sharing QGLWidgets. One is made current in the main GUI thread, while the other is made current in the texture upload thread. The widget in the uploading thread is never shown, it is only used for sharing textures with the main thread. For each texture that is bound via :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.bindTexture`, notify the main thread so that it can start using the texture.

* 3. Using :sip:ref:`~PyQt5.QtGui.QPainter` to draw into a :sip:ref:`~PyQt5.QtOpenGL.QGLWidget` in a thread.

  In Qt 4.8, it is possible to draw into a :sip:ref:`~PyQt5.QtOpenGL.QGLWidget` using a :sip:ref:`~PyQt5.QtGui.QPainter` in a separate thread. Note that this is also possible for QGLPixelBuffers and QGLFramebufferObjects. Since this is only supported in the GL 2 paint engine, OpenGL 2.0 or OpenGL ES 2.0 is required.

  QGLWidgets can only be created in the main GUI thread. This means a call to :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.doneCurrent` is necessary to release the GL context from the main thread, before the widget can be drawn into by another thread. You then need to call QGLContext::moveToThread() to transfer ownership of the context to the thread in which you want to make it current. Also, the main GUI thread will dispatch resize and paint events to a :sip:ref:`~PyQt5.QtOpenGL.QGLWidget` when the widget is resized, or parts of it becomes exposed or needs redrawing. It is therefore necessary to handle those events because the default implementations inside :sip:ref:`~PyQt5.QtOpenGL.QGLWidget` will try to make the :sip:ref:`~PyQt5.QtOpenGL.QGLWidget`'s context current, which again will interfere with any threads rendering into the widget. Reimplement :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.paintEvent` and :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.resizeEvent` to notify the rendering thread that a resize or update is necessary, and be careful not to call the base class implementation. If you are rendering an animation, it might not be necessary to handle the paint event at all since the rendering thread is doing regular updates. Then it would be enough to reimplement :sip:ref:`~PyQt5.QtOpenGL.QGLWidget.paintEvent` to do nothing.

As a general rule when doing threaded rendering: be aware that binding and releasing contexts in different threads have to be synchronized by the user. A GL rendering context can only be current in one thread at any time. If you try to open a :sip:ref:`~PyQt5.QtGui.QPainter` on a :sip:ref:`~PyQt5.QtOpenGL.QGLWidget` and the widget's rendering context is current in another thread, it will fail.

In addition to this, rendering using raw GL calls in a separate thread is supported.

*OpenGL is a trademark of Silicon Graphics, Inc. in the United States and other countries.*

.. seealso:: QGLPixelBuffer, :sip:ref:`~PyQt5.QtWidgets.QOpenGLWidget`.
