.. sip:method-description::
    :status: todo
    :pysig: 2a25b348a59d87879f518122c6f948a6
    :realsig: () const
    :digest: 48eb94d27505d9b834225b7d1e649a84

Returns the rect for this touch point in screen coordinates.

**Note:** This function returns an empty rect if the device does not report touch point sizes.

touchpoint regardless of rotation, whereas a touchpoint is more correctly modeled as an ellipse at position :sip:ref:`~PyQt5.QtGui.QTouchEvent.TouchPoint.screenPos` with ellipseDiameters() which are independent of rotation().

.. seealso:: :sip:ref:`~PyQt5.QtGui.QTouchEvent.TouchPoint.screenPos`.
