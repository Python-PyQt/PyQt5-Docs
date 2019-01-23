.. sip:method-description::
    :status: todo
    :pysig: e6f793ede99782d3cd029e7921c36913
    :realsig: () const
    :digest: 310a9d9727d846a20e7d8dd6e862b457

Returns the current clip path in logical coordinates.

**Warning:** :sip:ref:`~PyQt5.QtGui.QPainter` does not store the combined clip explicitly as this is handled by the underlying :sip:ref:`~PyQt5.QtGui.QPaintEngine`, so the path is recreated on demand and transformed to the current logical coordinate system. This is potentially an expensive operation.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPainter.setClipPath`, :sip:ref:`~PyQt5.QtGui.QPainter.clipRegion`, :sip:ref:`~PyQt5.QtGui.QPainter.setClipping`.
