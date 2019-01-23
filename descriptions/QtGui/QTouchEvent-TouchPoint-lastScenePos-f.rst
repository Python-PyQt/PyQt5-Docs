.. sip:method-description::
    :status: todo
    :pysig: 3c262cc6fe718e83c8acc57a39925789
    :realsig: () const
    :digest: a47b3864bef7e06ab18d22eed2ee7536

Returns the scene position of this touch point from the previous touch event.

The scene position is the position in QGraphicsScene coordinates if the :sip:ref:`~PyQt5.QtGui.QTouchEvent` is handled by a QGraphicsItem::touchEvent() reimplementation, and identical to the screen position for widgets.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QTouchEvent.TouchPoint.scenePos`, :sip:ref:`~PyQt5.QtGui.QTouchEvent.TouchPoint.startScenePos`.
