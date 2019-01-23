.. sip:class-description::
    :status: todo
    :brief: Event that is generated when a QAction is added, removed, or changed
    :digest: 1d133cfc6c40767d7801a672a8313569

The :sip:ref:`~PyQt5.QtGui.QActionEvent` class provides an event that is generated when a QAction is added, removed, or changed.

Actions can be added to widgets using :sip:ref:`~PyQt5.QtWidgets.QWidget.addAction`. This generates an :sip:ref:`~PyQt5.QtCore.QEvent.Type.ActionAdded` event, which you can handle to provide custom behavior. For example, QToolBar reimplements :sip:ref:`~PyQt5.QtWidgets.QWidget.actionEvent` to create QToolButtons for the actions.

.. seealso:: :sip:ref:`~PyQt5.QtWidgets.QWidget.addAction`, :sip:ref:`~PyQt5.QtWidgets.QWidget.removeAction`, :sip:ref:`~PyQt5.QtWidgets.QWidget.actions`, :sip:ref:`~PyQt5.QtWidgets.QAction`.
