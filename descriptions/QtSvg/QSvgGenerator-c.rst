.. sip:class-description::
    :status: todo
    :brief: Paint device that is used to create SVG drawings
    :digest: 43cef6effd6c7575f05939911440fd7e

The :sip:ref:`~PyQt5.QtSvg.QSvgGenerator` class provides a paint device that is used to create SVG drawings.

This paint device represents a Scalable Vector Graphics (SVG) drawing. Like QPrinter, it is designed as a write-only device that generates output in a specific format.

To write an SVG file, you first need to configure the output by setting the :sip:ref:`~PyQt5.QtSvg.QSvgGenerator.fileName` or :sip:ref:`~PyQt5.QtSvg.QSvgGenerator.outputDevice` properties. It is usually necessary to specify the size of the drawing by setting the :sip:ref:`~PyQt5.QtSvg.QSvgGenerator.size` property, and in some cases where the drawing will be included in another, the :sip:ref:`~PyQt5.QtSvg.QSvgGenerator.viewBox` property also needs to be set.

.. literalinclude:: ../../../snippets/qtsvg-examples-svg-svggenerator-window.py

Other meta-data can be specified by setting the *title*, *description* and *resolution* properties.

As with other :sip:ref:`~PyQt5.QtGui.QPaintDevice` subclasses, a :sip:ref:`~PyQt5.QtGui.QPainter` object is used to paint onto an instance of this class:

.. literalinclude:: ../../../snippets/qtsvg-examples-svg-svggenerator-window.py

.. literalinclude:: ../../../snippets/qtsvg-examples-svg-svggenerator-window.py

Painting is performed in the same way as for any other paint device. However, it is necessary to use the :sip:ref:`~PyQt5.QtGui.QPainter.begin` and :sip:ref:`~PyQt5.QtGui.QPainter.end` to explicitly begin and end painting on the device.

The `SVG Generator Example <https://doc.qt.io/qt-5/qtsvg-svggenerator-example.html>`_ shows how the same painting commands can be used for painting a widget and writing an SVG file.

.. seealso:: :sip:ref:`~PyQt5.QtSvg.QSvgRenderer`, :sip:ref:`~PyQt5.QtSvg.QSvgWidget`, :sip:ref:`~PyQt5.Qt SVG C++ Classes`.
