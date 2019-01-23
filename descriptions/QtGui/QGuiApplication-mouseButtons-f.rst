.. sip:method-description::
    :status: todo
    :pysig: 4d1307215a01fb7835ef39d5719c3d0b
    :realsig: ()
    :digest: c6a49f45a6561f5ba81f3e634ba8d46f

Returns the current state of the buttons on the mouse. The current state is updated synchronously as the event queue is emptied of events that will spontaneously change the mouse state (\ :sip:ref:`~PyQt5.QtCore.QEvent.Type.MouseButtonPress` and :sip:ref:`~PyQt5.QtCore.QEvent.Type.MouseButtonRelease` events).

It should be noted this may not reflect the actual buttons held on the input device at the time of calling but rather the mouse buttons as last reported in one of the above events. If no mouse buttons are being held :sip:ref:`~PyQt5.QtCore.Qt.MouseButton.NoButton` is returned.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QGuiApplication.keyboardModifiers`.
