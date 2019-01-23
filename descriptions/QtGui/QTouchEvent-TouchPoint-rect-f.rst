.. sip:method-description::
    :status: todo
    :pysig: 2a25b348a59d87879f518122c6f948a6
    :realsig: () const
    :digest: 591a33a94e4c032f1ffcf608d8cb23ed

Returns the rect for this touch point, relative to the widget or QGraphicsItem that received the event. The rect is centered around the point returned by :sip:ref:`~PyQt5.QtGui.QTouchEvent.TouchPoint.pos`.

**Note:** This function returns an empty rect if the device does not report touch point sizes.

of the touchpoint regardless of rotation, whereas a touchpoint is more correctly modeled as an ellipse at position :sip:ref:`~PyQt5.QtGui.QTouchEvent.TouchPoint.pos` with ellipseDiameters() which are independent of rotation().

.. seealso:: :sip:ref:`~PyQt5.QtGui.QTouchEvent.TouchPoint.scenePos`.
