.. sip:class-description::
    :status: todo
    :brief: Defines how a QPainter should draw lines and outlines of shapes
    :digest: 9058e6e50dfa623cb4dffb77f1085f4e

The :sip:ref:`~PyQt5.QtGui.QPen` class defines how a :sip:ref:`~PyQt5.QtGui.QPainter` should draw lines and outlines of shapes.

A pen has a :sip:ref:`~PyQt5.QtGui.QPen.style`, :sip:ref:`~PyQt5.QtGui.QPen.width`, :sip:ref:`~PyQt5.QtGui.QPen.brush`, :sip:ref:`~PyQt5.QtGui.QPen.capStyle` and :sip:ref:`~PyQt5.QtGui.QPen.joinStyle`.

The pen style defines the line type. The brush is used to fill strokes generated with the pen. Use the :sip:ref:`~PyQt5.QtGui.QBrush` class to specify fill styles. The cap style determines the line end caps that can be drawn using :sip:ref:`~PyQt5.QtGui.QPainter`, while the join style describes how joins between two lines are drawn. The pen width can be specified in both integer (\ :sip:ref:`~PyQt5.QtGui.QPen.width`) and floating point (\ :sip:ref:`~PyQt5.QtGui.QPen.widthF`) precision. A line width of zero indicates a cosmetic pen. This means that the pen width is always drawn one pixel wide, independent of the transformation set on the painter.

The various settings can easily be modified using the corresponding :sip:ref:`~PyQt5.QtGui.QPen.setStyle`, :sip:ref:`~PyQt5.QtGui.QPen.setWidth`, :sip:ref:`~PyQt5.QtGui.QPen.setBrush`, :sip:ref:`~PyQt5.QtGui.QPen.setCapStyle` and :sip:ref:`~PyQt5.QtGui.QPen.setJoinStyle` functions (note that the painter's pen must be reset when altering the pen's properties).

For example:

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-code-src_gui_painting_qpen.py
    :lines: 54-56

which is equivalent to

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-code-src_gui_painting_qpen.py
    :lines: 61-70

The default pen is a solid black brush with 1 width, square cap style (\ :sip:ref:`~PyQt5.QtCore.Qt.PenCapStyle.SquareCap`), and bevel join style (\ :sip:ref:`~PyQt5.QtCore.Qt.PenJoinStyle.BevelJoin`).

In addition :sip:ref:`~PyQt5.QtGui.QPen` provides the :sip:ref:`~PyQt5.QtGui.QPen.color` and :sip:ref:`~PyQt5.QtGui.QPen.setColor` convenience functions to extract and set the color of the pen's brush, respectively. Pens may also be compared and streamed.

For more information about painting in general, see the `Paint System <https://doc.qt.io/qt-5/paintsystem.html>`_ documentation.

.. _qpen-pen-style:

Pen Style
---------

Qt provides several built-in styles represented by the :sip:ref:`~PyQt5.QtCore.Qt.PenStyle` enum:

+--------------------------------------------------+-----------------------------------------------------+-----------------------------------------------------+
| |image-qpen-solid-png|                           | |image-qpen-dash-png|                               | |image-qpen-dot-png|                                |
+--------------------------------------------------+-----------------------------------------------------+-----------------------------------------------------+
| :sip:ref:`~PyQt5.QtCore.Qt.PenStyle.SolidLine`   | :sip:ref:`~PyQt5.QtCore.Qt.PenStyle.DashLine`       | :sip:ref:`~PyQt5.QtCore.Qt.PenStyle.DotLine`        |
+--------------------------------------------------+-----------------------------------------------------+-----------------------------------------------------+
| |image-qpen-dashdot-png|                         | |image-qpen-dashdotdot-png|                         | |image-qpen-custom-png|                             |
+--------------------------------------------------+-----------------------------------------------------+-----------------------------------------------------+
| :sip:ref:`~PyQt5.QtCore.Qt.PenStyle.DashDotLine` | :sip:ref:`~PyQt5.QtCore.Qt.PenStyle.DashDotDotLine` | :sip:ref:`~PyQt5.QtCore.Qt.PenStyle.CustomDashLine` |
+--------------------------------------------------+-----------------------------------------------------+-----------------------------------------------------+

Simply use the :sip:ref:`~PyQt5.QtGui.QPen.setStyle` function to convert the pen style to either of the built-in styles, except the :sip:ref:`~PyQt5.QtCore.Qt.PenStyle.CustomDashLine` style which we will come back to shortly. Setting the style to :sip:ref:`~PyQt5.QtCore.Qt.PenStyle.NoPen` tells the painter to not draw lines or outlines. The default pen style is :sip:ref:`~PyQt5.QtCore.Qt.PenStyle.SolidLine`.

Since Qt 4.1 it is also possible to specify a custom dash pattern using the :sip:ref:`~PyQt5.QtGui.QPen.setDashPattern` function which implicitly converts the style of the pen to :sip:ref:`~PyQt5.QtCore.Qt.PenStyle.CustomDashLine`. The pattern argument, a QVector, must be specified as an even number of qreal entries where the entries 1, 3, 5... are the dashes and 2, 4, 6... are the spaces. For example, the custom pattern shown above is created using the following code:

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-code-src_gui_painting_qpen.py
    :lines: 75-82

Note that the dash pattern is specified in units of the pens width, e.g. a dash of length 5 in width 10 is 50 pixels long.

The currently set dash pattern can be retrieved using the :sip:ref:`~PyQt5.QtGui.QPen.dashPattern` function. Use the :sip:ref:`~PyQt5.QtGui.QPen.isSolid` function to determine whether the pen has a solid fill, or not.

.. _qpen-cap-style:

Cap Style
---------

The cap style defines how the end points of lines are drawn using :sip:ref:`~PyQt5.QtGui.QPainter`. The cap style only apply to wide lines, i.e. when the width is 1 or greater. The :sip:ref:`~PyQt5.QtCore.Qt.PenCapStyle` enum provides the following styles:

+---------------------------------------------------+-------------------------------------------------+--------------------------------------------------+
| |image-qpen-square-png|                           | |image-qpen-flat-png|                           | |image-qpen-roundcap-png|                        |
+---------------------------------------------------+-------------------------------------------------+--------------------------------------------------+
| :sip:ref:`~PyQt5.QtCore.Qt.PenCapStyle.SquareCap` | :sip:ref:`~PyQt5.QtCore.Qt.PenCapStyle.FlatCap` | :sip:ref:`~PyQt5.QtCore.Qt.PenCapStyle.RoundCap` |
+---------------------------------------------------+-------------------------------------------------+--------------------------------------------------+

The :sip:ref:`~PyQt5.QtCore.Qt.PenCapStyle.SquareCap` style is a square line end that covers the end point and extends beyond it by half the line width. The :sip:ref:`~PyQt5.QtCore.Qt.PenCapStyle.FlatCap` style is a square line end that does not cover the end point of the line. And the :sip:ref:`~PyQt5.QtCore.Qt.PenCapStyle.RoundCap` style is a rounded line end covering the end point.

The default is :sip:ref:`~PyQt5.QtCore.Qt.PenCapStyle.SquareCap`.

Whether or not end points are drawn when the pen width is 0 or 1 depends on the cap style. Using :sip:ref:`~PyQt5.QtCore.Qt.PenCapStyle.SquareCap` or :sip:ref:`~PyQt5.QtCore.Qt.PenCapStyle.RoundCap` they are drawn, using :sip:ref:`~PyQt5.QtCore.Qt.PenCapStyle.FlatCap` they are not drawn.

.. _qpen-join-style:

Join Style
----------

The join style defines how joins between two connected lines can be drawn using :sip:ref:`~PyQt5.QtGui.QPainter`. The join style only apply to wide lines, i.e. when the width is 1 or greater. The :sip:ref:`~PyQt5.QtCore.Qt.PenJoinStyle` enum provides the following styles:

+----------------------------------------------------+----------------------------------------------------+----------------------------------------------------+
| |image-qpen-bevel-png|                             | |image-qpen-miter-png|                             | |image-qpen-roundjoin-png|                         |
+----------------------------------------------------+----------------------------------------------------+----------------------------------------------------+
| :sip:ref:`~PyQt5.QtCore.Qt.PenJoinStyle.BevelJoin` | :sip:ref:`~PyQt5.QtCore.Qt.PenJoinStyle.MiterJoin` | :sip:ref:`~PyQt5.QtCore.Qt.PenJoinStyle.RoundJoin` |
+----------------------------------------------------+----------------------------------------------------+----------------------------------------------------+

The :sip:ref:`~PyQt5.QtCore.Qt.PenJoinStyle.BevelJoin` style fills the triangular notch between the two lines. The :sip:ref:`~PyQt5.QtCore.Qt.PenJoinStyle.MiterJoin` style extends the lines to meet at an angle. And the :sip:ref:`~PyQt5.QtCore.Qt.PenJoinStyle.RoundJoin` style fills a circular arc between the two lines.

The default is :sip:ref:`~PyQt5.QtCore.Qt.PenJoinStyle.BevelJoin`.

.. image:: ../../../images/qpen-miterlimit.png

When the :sip:ref:`~PyQt5.QtCore.Qt.PenJoinStyle.MiterJoin` style is applied, it is possible to use the :sip:ref:`~PyQt5.QtGui.QPen.setMiterLimit` function to specify how far the miter join can extend from the join point. The :sip:ref:`~PyQt5.QtGui.QPen.miterLimit` is used to reduce artifacts between line joins where the lines are close to parallel.

The :sip:ref:`~PyQt5.QtGui.QPen.miterLimit` must be specified in units of the pens width, e.g. a miter limit of 5 in width 10 is 50 pixels long. The default miter limit is 2, i.e. twice the pen width in pixels.

+-----------------------+--------------------------------------------------------------------------------------------------------------------------------------------------+
| |image-qpen-demo-png| | **`The Path Stroking Example <https://doc.qt.io/qt-5/qtwidgets-painting-pathstroke-example.html>`_**                                             |
|                       |                                                                                                                                                  |
|                       | The Path Stroking example shows Qt's built-in dash patterns and shows how custom patterns can be used to extend the range of available patterns. |
+-----------------------+--------------------------------------------------------------------------------------------------------------------------------------------------+

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPainter`, :sip:ref:`~PyQt5.QtGui.QBrush`, `Path Stroking Example <https://doc.qt.io/qt-5/qtwidgets-painting-pathstroke-example.html>`_, `Scribble Example <https://doc.qt.io/qt-5/qtwidgets-widgets-scribble-example.html>`_.

.. |image-qpen-solid-png| image:: ../../../images/qpen-solid.png
.. |image-qpen-dash-png| image:: ../../../images/qpen-dash.png
.. |image-qpen-dot-png| image:: ../../../images/qpen-dot.png
.. |image-qpen-dashdot-png| image:: ../../../images/qpen-dashdot.png
.. |image-qpen-dashdotdot-png| image:: ../../../images/qpen-dashdotdot.png
.. |image-qpen-custom-png| image:: ../../../images/qpen-custom.png
.. |image-qpen-square-png| image:: ../../../images/qpen-square.png
.. |image-qpen-flat-png| image:: ../../../images/qpen-flat.png
.. |image-qpen-roundcap-png| image:: ../../../images/qpen-roundcap.png
.. |image-qpen-bevel-png| image:: ../../../images/qpen-bevel.png
.. |image-qpen-miter-png| image:: ../../../images/qpen-miter.png
.. |image-qpen-roundjoin-png| image:: ../../../images/qpen-roundjoin.png
.. |image-qpen-demo-png| image:: ../../../images/qpen-demo.png
