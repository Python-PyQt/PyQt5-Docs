.. sip:class-description::
    :status: todo
    :brief: Vector of points using floating point precision
    :digest: 40d3097853ebdc27df5888698e78e312

The :sip:ref:`~PyQt5.QtGui.QPolygonF` class provides a vector of points using floating point precision.

A :sip:ref:`~PyQt5.QtGui.QPolygonF` is a QVector<\ :sip:ref:`~PyQt5.QtCore.QPointF`>. The easiest way to add points to a :sip:ref:`~PyQt5.QtGui.QPolygonF` is to use its streaming operator, as illustrated below:

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-polygon-polygon.py
    :lines: 68-69

In addition to the functions provided by QVector, :sip:ref:`~PyQt5.QtGui.QPolygonF` provides the :sip:ref:`~PyQt5.QtGui.QPolygonF.boundingRect` and :sip:ref:`~PyQt5.QtGui.QPolygonF.translate` functions for geometry operations. Use the QMatrix::map() function for more general transformations of QPolygonFs.

:sip:ref:`~PyQt5.QtGui.QPolygonF` also provides the :sip:ref:`~PyQt5.QtGui.QPolygonF.isClosed` function to determine whether a polygon's start and end points are the same, and the :sip:ref:`~PyQt5.QtGui.QPolygonF.toPolygon` function returning an integer precision copy of this polygon.

The :sip:ref:`~PyQt5.QtGui.QPolygonF` class is `implicitly shared <https://doc.qt.io/qt-5/implicit-sharing.html>`_.

.. seealso:: QVector, :sip:ref:`~PyQt5.QtGui.QPolygon`, :sip:ref:`~PyQt5.QtCore.QLineF`.
