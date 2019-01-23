.. sip:method-description::
    :status: todo
    :pysig: 68a028ec030aafa338e6f53c0d3872ab
    :realsig: (const QGLContext*)
    :digest: f2135f6651e302dbfc7e5f2839ceba4e

Creates the GL context. Returns ``true`` if it was successful in creating a valid GL rendering context on the paint device specified in the constructor; otherwise returns ``false`` (i.e. the context is invalid).

If the OpenGL implementation on your system does not support the requested version of OpenGL context, then :sip:ref:`~PyQt5.QtOpenGL.QGLContext` will try to create the closest matching version. The actual created context properties can be queried using the :sip:ref:`~PyQt5.QtOpenGL.QGLFormat` returned by the :sip:ref:`~PyQt5.QtOpenGL.QGLContext.format` function. For example, if you request a context that supports OpenGL 4.3 Core profile but the driver and/or hardware only supports version 3.2 Core profile contexts then you will get a 3.2 Core profile context.

After successful creation, :sip:ref:`~PyQt5.QtOpenGL.QGLContext.format` returns the set of features of the created GL rendering context.

If *shareContext* points to a valid :sip:ref:`~PyQt5.QtOpenGL.QGLContext`, this method will try to establish OpenGL display list and texture object sharing between this context and the *shareContext*. Note that this may fail if the two contexts have different :sip:ref:`~PyQt5.QtOpenGL.QGLContext.format`. Use :sip:ref:`~PyQt5.QtOpenGL.QGLContext.isSharing` to see if sharing is in effect.

**Warning:** Implementation note: initialization of C++ class members usually takes place in the class constructor. :sip:ref:`~PyQt5.QtOpenGL.QGLContext` is an exception because it must be simple to customize. The virtual functions :sip:ref:`~PyQt5.QtOpenGL.QGLContext.chooseContext` (and chooseVisual() for X11) can be reimplemented in a subclass to select a particular context. The problem is that virtual functions are not properly called during construction (even though this is correct C++) because C++ constructs class hierarchies from the bottom up. For this reason we need a  function.

.. seealso:: :sip:ref:`~PyQt5.QtOpenGL.QGLContext.chooseContext`, :sip:ref:`~PyQt5.QtOpenGL.QGLContext.format`, :sip:ref:`~PyQt5.QtOpenGL.QGLContext.isValid`.
