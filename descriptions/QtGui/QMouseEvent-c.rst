.. sip:class-description::
    :status: todo
    :brief: Contains parameters that describe a mouse event
    :digest: c72359a0b671d81fda5a51506af0db1a

The :sip:ref:`~PyQt5.QtGui.QMouseEvent` class contains parameters that describe a mouse event.

Mouse events occur when a mouse button is pressed or released inside a widget, or when the mouse cursor is moved.

Mouse move events will occur only when a mouse button is pressed down, unless mouse tracking has been enabled with :sip:ref:`~PyQt5.QtWidgets.QWidget.setMouseTracking`.

Qt automatically grabs the mouse when a mouse button is pressed inside a widget; the widget will continue to receive mouse events until the last mouse button is released.

A mouse event contains a special accept flag that indicates whether the receiver wants the event. You should call ignore() if the mouse event is not handled by your widget. A mouse event is propagated up the parent widget chain until a widget accepts it with accept(), or an event filter consumes it.

**Note:** If a mouse event is propagated to a :sip:ref:`~PyQt5.QtWidgets.QWidget` for which :sip:ref:`~PyQt5.QtCore.Qt.WidgetAttribute.WA_NoMousePropagation` has been set, that mouse event will not be propagated further up the parent widget chain.

The state of the keyboard modifier keys can be found by calling the :sip:ref:`~PyQt5.QtGui.QInputEvent.modifiers` function, inherited from :sip:ref:`~PyQt5.QtGui.QInputEvent`.

The functions :sip:ref:`~PyQt5.QtGui.QMouseEvent.pos`, :sip:ref:`~PyQt5.QtGui.QMouseEvent.x`, and :sip:ref:`~PyQt5.QtGui.QMouseEvent.y` give the cursor position relative to the widget that receives the mouse event. If you move the widget as a result of the mouse event, use the global position returned by :sip:ref:`~PyQt5.QtGui.QMouseEvent.globalPos` to avoid a shaking motion.

The :sip:ref:`~PyQt5.QtWidgets.QWidget.setEnabled` function can be used to enable or disable mouse and keyboard events for a widget.

Reimplement the :sip:ref:`~PyQt5.QtWidgets.QWidget` event handlers, :sip:ref:`~PyQt5.QtWidgets.QWidget.mousePressEvent`, :sip:ref:`~PyQt5.QtWidgets.QWidget.mouseReleaseEvent`, :sip:ref:`~PyQt5.QtWidgets.QWidget.mouseDoubleClickEvent`, and :sip:ref:`~PyQt5.QtWidgets.QWidget.mouseMoveEvent` to receive mouse events in your own widgets.

.. seealso:: :sip:ref:`~PyQt5.QtWidgets.QWidget.setMouseTracking`, :sip:ref:`~PyQt5.QtWidgets.QWidget.grabMouse`.
