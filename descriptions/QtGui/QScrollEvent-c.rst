.. sip:class-description::
    :status: todo
    :brief: Sent when scrolling
    :digest: 72794dca70979b3e2c939166eadce00f

The :sip:ref:`~PyQt5.QtGui.QScrollEvent` class is sent when scrolling.

The scroll event is sent to indicate that the receiver should be scrolled. Usually the receiver should be something visual like :sip:ref:`~PyQt5.QtWidgets.QWidget` or QGraphicsObject.

Some care should be taken that no conflicting QScrollEvents are sent from two sources. Using QScroller::scrollTo is save however.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QScrollPrepareEvent`.
