.. sip:class-description::
    :status: todo
    :brief: Event which is sent while a drag and drop action is in progress
    :digest: dfeae9c7ddb03754d59f5aea6b9546f6

The :sip:ref:`~PyQt5.QtGui.QDragMoveEvent` class provides an event which is sent while a drag and drop action is in progress.

A widget will receive drag move events repeatedly while the drag is within its boundaries, if it accepts :sip:ref:`~PyQt5.QtWidgets.QWidget.setAcceptDrops` and enter events. The widget should examine the event to see what kind of data it provides, and call the :sip:ref:`~PyQt5.QtGui.QDragMoveEvent.accept` function to accept the drop if appropriate.

The rectangle supplied by the :sip:ref:`~PyQt5.QtGui.QDragMoveEvent.answerRect` function can be used to restrict drops to certain parts of the widget. For example, we can check whether the rectangle intersects with the geometry of a certain child widget and only call :sip:ref:`~PyQt5.QtGui.QDropEvent.acceptProposedAction` if that is the case.

Note that this class inherits most of its functionality from :sip:ref:`~PyQt5.QtGui.QDropEvent`.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QDragEnterEvent`, :sip:ref:`~PyQt5.QtGui.QDragLeaveEvent`, :sip:ref:`~PyQt5.QtGui.QDropEvent`.
