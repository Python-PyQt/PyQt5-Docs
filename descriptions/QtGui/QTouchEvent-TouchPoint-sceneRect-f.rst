.. sip:method-description::
    :status: todo
    :pysig: 2a25b348a59d87879f518122c6f948a6
    :realsig: () const
    :digest: 3b16aea4def85f9f016a6eea57a763a7

Returns the rect for this touch point in scene coordinates.

**Note:** This function returns an empty rect if the device does not report touch point sizes.

of the touchpoint regardless of rotation, whereas a touchpoint is more correctly modeled as an ellipse at position :sip:ref:`~PyQt5.QtGui.QTouchEvent.TouchPoint.scenePos` with ellipseDiameters() which are independent of rotation().

.. seealso:: :sip:ref:`~PyQt5.QtGui.QTouchEvent.TouchPoint.scenePos`.
