.. sip:class-description::
    :status: todo
    :brief: QOpenGLVertexArrayObject::Binder class is a convenience class to help with the binding and releasing of OpenGL Vertex Array Objects
    :digest: dd65c1e9ca30466ef9883217b3ad27e6

The :sip:ref:`~PyQt5.QtGui.QOpenGLVertexArrayObject.Binder` class is a convenience class to help with the binding and releasing of OpenGL Vertex Array Objects.

:sip:ref:`~PyQt5.QtGui.QOpenGLVertexArrayObject.Binder` is a simple convenience class that can be used to assist with the binding and releasing of :sip:ref:`~PyQt5.QtGui.QOpenGLVertexArrayObject` instances. This class is to :sip:ref:`~PyQt5.QtGui.QOpenGLVertexArrayObject` as :sip:ref:`~PyQt5.QtCore.QMutexLocker` is to :sip:ref:`~PyQt5.QtCore.QMutex`.

This class implements the RAII principle which helps to ensure behavior in complex code or in the presence of exceptions.

The constructor of this class accepts a :sip:ref:`~PyQt5.QtGui.QOpenGLVertexArrayObject` (VAO) as an argument and attempts to bind the VAO, calling :sip:ref:`~PyQt5.QtGui.QOpenGLVertexArrayObject.create` if necessary. The destructor of this class calls :sip:ref:`~PyQt5.QtGui.QOpenGLVertexArrayObject.release` which unbinds the VAO.

If needed the VAO can be temporarily unbound with the :sip:ref:`~PyQt5.QtGui.QOpenGLVertexArrayObject.Binder.release` function and bound once more with :sip:ref:`~PyQt5.QtGui.QOpenGLVertexArrayObject.Binder.rebind`.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOpenGLVertexArrayObject`.
