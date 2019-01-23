.. sip:class-description::
    :status: todo
    :brief: Contains event parameters for widget focus events
    :digest: 287927310c919c06213c9fda9e172a12

The :sip:ref:`~PyQt5.QtGui.QFocusEvent` class contains event parameters for widget focus events.

Focus events are sent to widgets when the keyboard input focus changes. Focus events occur due to mouse actions, key presses (such as Tab or Backtab), the window system, popup menus, keyboard shortcuts, or other application-specific reasons. The reason for a particular focus event is returned by :sip:ref:`~PyQt5.QtGui.QFocusEvent.reason` in the appropriate event handler.

The event handlers :sip:ref:`~PyQt5.QtWidgets.QWidget.focusInEvent`, :sip:ref:`~PyQt5.QtWidgets.QWidget.focusOutEvent`, QGraphicsItem::focusInEvent and QGraphicsItem::focusOutEvent() receive focus events.

.. seealso:: :sip:ref:`~PyQt5.QtWidgets.QWidget.setFocus`, :sip:ref:`~PyQt5.QtWidgets.QWidget.setFocusPolicy`, `Keyboard Focus in Widgets <https://doc.qt.io/qt-5/focus.html>`_.
