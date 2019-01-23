.. sip:class-description::
    :status: todo
    :brief: Contains parameters that describe a wheel event
    :digest: 4924ab4c53d9cb8df91b2d4c5e541cbd

The :sip:ref:`~PyQt5.QtGui.QWheelEvent` class contains parameters that describe a wheel event.

Wheel events are sent to the widget under the mouse cursor, but if that widget does not handle the event they are sent to the focus widget. Wheel events are generated for both mouse wheels and trackpad scroll gestures. There are two ways to read the wheel event delta: angleDelta() returns the delta in wheel degrees. This value is always provided. pixelDelta() returns the delta in screen pixels and is available on platforms that have high-resolution trackpads, such as `macOS <https://doc.qt.io/qt-5/qtwebengine-platform-notes.html#macos>`_. If that is the case, `source() <https://doc.qt.io/qt-5/qtremoteobjects-source.html#source>`_ will return Qt::MouseEventSynthesizedBySystem.

The functions :sip:ref:`~PyQt5.QtGui.QWheelEvent.pos` and :sip:ref:`~PyQt5.QtGui.QWheelEvent.globalPos` return the mouse cursor's location at the time of the event.

A wheel event contains a special accept flag that indicates whether the receiver wants the event. You should call ignore() if you do not handle the wheel event; this ensures that it will be sent to the parent widget.

The :sip:ref:`~PyQt5.QtWidgets.QWidget.setEnabled` function can be used to enable or disable mouse and keyboard events for a widget.

The event handler QWidget::wheelEvent() receives wheel events.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QMouseEvent`, :sip:ref:`~PyQt5.QtWidgets.QWidget.grabMouse`.
