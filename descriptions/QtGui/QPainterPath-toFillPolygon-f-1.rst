.. sip:method-description::
    :status: todo
    :pysig: c90048e7d0e60e947461116837413cc7
    :realsig: (const QTransform&) const
    :digest: 32a5c94ef5aa14e5aff7aaed215e4221

Converts the path into a polygon using the :sip:ref:`~PyQt5.QtGui.QTransform` *matrix*, and returns the polygon.

The polygon is created by first converting all subpaths to polygons, then using a rewinding technique to make sure that overlapping subpaths can be filled using the correct fill rule.

Note that rewinding inserts addition lines in the polygon so the outline of the fill polygon does not match the outline of the path.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPainterPath.toSubpathPolygons`, :sip:ref:`~PyQt5.QtGui.QPainterPath.toFillPolygons`, QPainterPath Conversion.
