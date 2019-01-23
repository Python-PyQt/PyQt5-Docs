.. sip:class-description::
    :status: todo
    :brief: Represents a native OpenGL context, enabling OpenGL rendering on a QSurface
    :digest: 4f43ca4993134d87a29fa1c2d6c26001

The :sip:ref:`~PyQt5.QtGui.QOpenGLContext` class represents a native OpenGL context, enabling OpenGL rendering on a :sip:ref:`~PyQt5.QtGui.QSurface`.

:sip:ref:`~PyQt5.QtGui.QOpenGLContext` represents the OpenGL state of an underlying OpenGL context. To set up a context, set its screen and format such that they match those of the surface or surfaces with which the context is meant to be used, if necessary make it share resources with other contexts with :sip:ref:`~PyQt5.QtGui.QOpenGLContext.setShareContext`, and finally call :sip:ref:`~PyQt5.QtGui.QOpenGLContext.create`. Use the return value or :sip:ref:`~PyQt5.QtGui.QOpenGLContext.isValid` to check if the context was successfully initialized.

A context can be made current against a given surface by calling :sip:ref:`~PyQt5.QtGui.QOpenGLContext.makeCurrent`. When OpenGL rendering is done, call :sip:ref:`~PyQt5.QtGui.QOpenGLContext.swapBuffers` to swap the front and back buffers of the surface, so that the newly rendered content becomes visible. To be able to support certain platforms, :sip:ref:`~PyQt5.QtGui.QOpenGLContext` requires that you call :sip:ref:`~PyQt5.QtGui.QOpenGLContext.makeCurrent` again before starting rendering a new frame, after calling :sip:ref:`~PyQt5.QtGui.QOpenGLContext.swapBuffers`.

If the context is temporarily not needed, such as when the application is not rendering, it can be useful to delete it in order to free resources. You can connect to the :sip:ref:`~PyQt5.QtGui.QOpenGLContext.aboutToBeDestroyed` signal to clean up any resources that have been allocated with different ownership from the :sip:ref:`~PyQt5.QtGui.QOpenGLContext` itself.

Once a :sip:ref:`~PyQt5.QtGui.QOpenGLContext` has been made current, you can render to it in a platform independent way by using Qt's OpenGL enablers such as QOpenGLFunctions, :sip:ref:`~PyQt5.QtGui.QOpenGLBuffer`, :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram`, and :sip:ref:`~PyQt5.QtGui.QOpenGLFramebufferObject`. It is also possible to use the platform's OpenGL API directly, without using the Qt enablers, although potentially at the cost of portability. The latter is necessary when wanting to use OpenGL 1.x or OpenGL ES 1.x.

For more information about the OpenGL API, refer to the official OpenGL documentation.

For an example of how to use :sip:ref:`~PyQt5.QtGui.QOpenGLContext` see the `OpenGL Window <https://doc.qt.io/qt-5/qtgui-openglwindow-example.html>`_ example.

.. _qopenglcontext-thread-affinity:

Thread Affinity
---------------

:sip:ref:`~PyQt5.QtGui.QOpenGLContext` can be moved to a different thread with moveToThread(). Do not call :sip:ref:`~PyQt5.QtGui.QOpenGLContext.makeCurrent` from a different thread than the one to which the :sip:ref:`~PyQt5.QtGui.QOpenGLContext` object belongs. A context can only be current in one thread and against one surface at a time, and a thread only has one context current at a time.

.. _qopenglcontext-context-resource-sharing:

Context Resource Sharing
------------------------

Resources, such as framebuffer objects, textures, and vertex buffer objects can be shared between contexts. Use :sip:ref:`~PyQt5.QtGui.QOpenGLContext.setShareContext` before calling :sip:ref:`~PyQt5.QtGui.QOpenGLContext.create` to specify that the contexts should share these resources. :sip:ref:`~PyQt5.QtGui.QOpenGLContext` internally keeps track of a :sip:ref:`~PyQt5.QtGui.QOpenGLContextGroup` object which can be accessed with :sip:ref:`~PyQt5.QtGui.QOpenGLContext.shareGroup`, and which can be used to find all the contexts in a given share group. A share group consists of all contexts that have been successfully initialized and are sharing with an existing context in the share group. A non-sharing context has a share group consisting of a single context.

.. _qopenglcontext-default-framebuffer:

Default Framebuffer
-------------------

On certain platforms, a framebuffer other than 0 might be the default frame buffer depending on the current surface. Instead of calling glBindFramebuffer(0), it is recommended that you use glBindFramebuffer(ctx->\ :sip:ref:`~PyQt5.QtGui.QOpenGLContext.defaultFramebufferObject`), to ensure that your application is portable between different platforms. However, if you use QOpenGLFunctions::glBindFramebuffer(), this is done automatically for you.

.. seealso:: QOpenGLFunctions, :sip:ref:`~PyQt5.QtGui.QOpenGLBuffer`, :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram`, :sip:ref:`~PyQt5.QtGui.QOpenGLFramebufferObject`.
