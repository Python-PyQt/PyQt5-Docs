.. sip:method-description::
    :status: todo
    :pysig: c8e367ce6313099b6fca25ac79d15930
    :realsig: (const QPolygonF&,const QPolygonF&,QTransform&)
    :digest: d87d9ea39ba35d099cea08d9437ae386

Creates a transformation matrix, *trans*, that maps a four-sided polygon, *one*, to another four-sided polygon, *two*. Returns ``true`` if the transformation is possible; otherwise returns false.

This is a convenience method combining :sip:ref:`~PyQt5.QtGui.QTransform.quadToSquare` and :sip:ref:`~PyQt5.QtGui.QTransform.squareToQuad` methods. It allows the input quad to be transformed into any other quad.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QTransform.squareToQuad`, :sip:ref:`~PyQt5.QtGui.QTransform.quadToSquare`.
