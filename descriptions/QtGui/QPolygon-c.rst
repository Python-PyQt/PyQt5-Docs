.. sip:class-description::
    :status: todo
    :brief: Vector of points using integer precision
    :digest: 4fd5f12cabda158909d4b3b8b96f1c23

The :sip:ref:`~PyQt5.QtGui.QPolygon` class provides a vector of points using integer precision.

A :sip:ref:`~PyQt5.QtGui.QPolygon` object is a QVector<\ :sip:ref:`~PyQt5.QtCore.QPoint`>. The easiest way to add points to a :sip:ref:`~PyQt5.QtGui.QPolygon` is to use QVector's streaming operator, as illustrated below:

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-polygon-polygon.py
    :lines: 60-61

In addition to the functions provided by QVector, :sip:ref:`~PyQt5.QtGui.QPolygon` provides some point-specific functions.

Each point in a polygon can be retrieved by passing its index to the :sip:ref:`~PyQt5.QtGui.QPolygon.point` function. To populate the polygon, :sip:ref:`~PyQt5.QtGui.QPolygon` provides the :sip:ref:`~PyQt5.QtGui.QPolygon.setPoint` function to set the point at a given index, the :sip:ref:`~PyQt5.QtGui.QPolygon.setPoints` function to set all the points in the polygon (resizing it to the given number of points), and the :sip:ref:`~PyQt5.QtGui.QPolygon.putPoints` function which copies a number of given points into the polygon from a specified index (resizing the polygon if necessary).

:sip:ref:`~PyQt5.QtGui.QPolygon` provides the :sip:ref:`~PyQt5.QtGui.QPolygon.boundingRect` and :sip:ref:`~PyQt5.QtGui.QPolygon.translate` functions for geometry functions. Use the QMatrix::map() function for more general transformations of QPolygons.

The :sip:ref:`~PyQt5.QtGui.QPolygon` class is `implicitly shared <https://doc.qt.io/qt-5/implicit-sharing.html>`_.

.. seealso:: QVector, :sip:ref:`~PyQt5.QtGui.QPolygonF`, :sip:ref:`~PyQt5.QtCore.QLine`.
