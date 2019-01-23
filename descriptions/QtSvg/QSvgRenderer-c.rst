.. sip:class-description::
    :status: todo
    :brief: Used to draw the contents of SVG files onto paint devices
    :digest: 35b8fbb3072ebb372e12483b8e5855d7

The :sip:ref:`~PyQt5.QtSvg.QSvgRenderer` class is used to draw the contents of SVG files onto paint devices.

Using :sip:ref:`~PyQt5.QtSvg.QSvgRenderer`, Scalable Vector Graphics (SVG) can be rendered onto any :sip:ref:`~PyQt5.QtGui.QPaintDevice` subclass, including :sip:ref:`~PyQt5.QtWidgets.QWidget`, :sip:ref:`~PyQt5.QtGui.QImage`, and :sip:ref:`~PyQt5.QtOpenGL.QGLWidget`.

:sip:ref:`~PyQt5.QtSvg.QSvgRenderer` provides an API that supports basic features of SVG rendering, such as loading and rendering of static drawings, and more interactive features like animation. Since the rendering is performed using :sip:ref:`~PyQt5.QtGui.QPainter`, SVG drawings can be rendered on any subclass of :sip:ref:`~PyQt5.QtGui.QPaintDevice`.

SVG drawings are either loaded when an :sip:ref:`~PyQt5.QtSvg.QSvgRenderer` is constructed, or loaded later using the :sip:ref:`~PyQt5.QtSvg.QSvgRenderer.load` functions. Data is either supplied directly as serialized XML, or indirectly using a file name. If a valid file has been loaded, either when the renderer is constructed or at some later time, :sip:ref:`~PyQt5.QtSvg.QSvgRenderer.isValid` returns true; otherwise it returns false. :sip:ref:`~PyQt5.QtSvg.QSvgRenderer` provides the :sip:ref:`~PyQt5.QtSvg.QSvgRenderer.render` slot to render the current document, or the current frame of an animated document, using a given painter.

The :sip:ref:`~PyQt5.QtSvg.QSvgRenderer.defaultSize` function provides information about the amount of space that is required to render the currently loaded SVG file. This is useful for paint devices, such as :sip:ref:`~PyQt5.QtWidgets.QWidget`, that often need to supply a size hint to their parent layout. The default size of a drawing may differ from its visible area, found using the :sip:ref:`~PyQt5.QtSvg.QSvgRenderer.viewBox` property.

Animated SVG drawings are supported, and can be controlled with a simple collection of functions and properties:

* The :sip:ref:`~PyQt5.QtSvg.QSvgRenderer.animated` function indicates whether a drawing contains animation information.

* The :sip:ref:`~PyQt5.QtSvg.QSvgRenderer.framesPerSecond` property contains the rate at which the animation plays.

Finally, the :sip:ref:`~PyQt5.QtSvg.QSvgRenderer` class provides the :sip:ref:`~PyQt5.QtSvg.QSvgRenderer.repaintNeeded` signal which is emitted whenever the rendering of the document needs to be updated.

.. seealso:: :sip:ref:`~PyQt5.QtSvg.QSvgWidget`, :sip:ref:`~PyQt5.Qt SVG C++ Classes`, `SVG Viewer Example <https://doc.qt.io/qt-5/qtsvg-svgviewer-example.html>`_, :sip:ref:`~PyQt5.QtGui.QPicture`.
