.. sip:method-description::
    :status: todo
    :pysig: 310cd3e0a237f2222b759579115b6cdc
    :realsig: (int) const
    :digest: b49dde9f079a2a261003486405645311

Returns the timeline value for the time *msec*. The returned value, which varies depending on the curve shape, is always between 0 and 1. If *msec* is 0, the default implementation always returns 0.

Reimplement this function to provide a custom curve shape for your timeline.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QTimeLine.CurveShape.CurveShape`, :sip:ref:`~PyQt5.QtCore.QTimeLine.frameForTime`.
