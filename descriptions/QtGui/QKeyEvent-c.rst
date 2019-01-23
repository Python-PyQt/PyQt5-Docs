.. sip:class-description::
    :status: todo
    :brief: Describes a key event
    :digest: 6e3badc95ee961f6445d550a0905e757

The :sip:ref:`~PyQt5.QtGui.QKeyEvent` class describes a key event.

Key events are sent to the widget with keyboard input focus when keys are pressed or released.

A key event contains a special accept flag that indicates whether the receiver will handle the key event. This flag is set by default for :sip:ref:`~PyQt5.QtCore.QEvent.Type.KeyPress` and :sip:ref:`~PyQt5.QtCore.QEvent.Type.KeyRelease`, so there is no need to call accept() when acting on a key event. For :sip:ref:`~PyQt5.QtCore.QEvent.Type.ShortcutOverride` the receiver needs to explicitly accept the event to trigger the override. Calling ignore() on a key event will propagate it to the parent widget. The event is propagated up the parent widget chain until a widget accepts it or an event filter consumes it.

The :sip:ref:`~PyQt5.QtWidgets.QWidget.setEnabled` function can be used to enable or disable mouse and keyboard events for a widget.

The event handlers :sip:ref:`~PyQt5.QtWidgets.QWidget.keyPressEvent`, :sip:ref:`~PyQt5.QtWidgets.QWidget.keyReleaseEvent`, QGraphicsItem::keyPressEvent() and QGraphicsItem::keyReleaseEvent() receive key events.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QFocusEvent`, :sip:ref:`~PyQt5.QtWidgets.QWidget.grabKeyboard`.
