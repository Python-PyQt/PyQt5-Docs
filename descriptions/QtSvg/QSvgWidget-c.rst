.. sip:class-description::
    :status: todo
    :brief: Widget that is used to display the contents of Scalable Vector Graphics (SVG) files
    :digest: 673a228acbd8e1cd376bb70072008a97

The :sip:ref:`~PyQt5.QtSvg.QSvgWidget` class provides a widget that is used to display the contents of Scalable Vector Graphics (SVG) files.

This class enables developers to display SVG drawings alongside standard widgets, and is used in much the same way as QLabel is used for displaying text and bitmap images.

Since :sip:ref:`~PyQt5.QtSvg.QSvgWidget` is a subclass of :sip:ref:`~PyQt5.QtWidgets.QWidget`, SVG drawings are rendered using the properties of the display. More control can be exercised over the rendering process with the :sip:ref:`~PyQt5.QtSvg.QSvgRenderer` class, as this can be used to paint onto other paint devices, such as :sip:ref:`~PyQt5.QtGui.QImage` and :sip:ref:`~PyQt5.QtOpenGL.QGLWidget`. The renderer used by the widget can be obtained with the  function.

Each :sip:ref:`~PyQt5.QtSvg.QSvgWidget` can be constructed with the file name of a SVG file, or they can be constructed without a specific file to render and one can be supplied later. The :sip:ref:`~PyQt5.QtSvg.QSvgWidget.load` functions provide two different ways to load an SVG file: they accept either the file name of an SVG file or a :sip:ref:`~PyQt5.QtCore.QByteArray` containing the serialized XML representation of an SVG file.

By default, the widget provides a size hint to reflect the size of the drawing that it displays. If no data has been loaded, the widget provides the default :sip:ref:`~PyQt5.QtWidgets.QWidget` size hint. Subclass this class and reimplement  if you need to customize this behavior.

.. seealso:: :sip:ref:`~PyQt5.QtSvg.QSvgRenderer`, :sip:ref:`~PyQt5.Qt SVG C++ Classes`, :sip:ref:`~PyQt5.QtGui.QPicture`.
