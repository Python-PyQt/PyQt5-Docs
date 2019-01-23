:orphan:

.. sip:class:: PyQt5.QtGui.QTouchEvent
    :inherits: :sip:ref:`~PyQt5.QtGui.QInputEvent`
    :description: QtGui/QTouchEvent-c.rst

    .. sip:method:: PyQt5.QtGui.QTouchEvent.__init__
        :args:
            :sip:ref:`~PyQt5.QtGui.QTouchEvent`
        :description: QtGui/QTouchEvent-__init__-f.rst

    .. sip:method:: PyQt5.QtGui.QTouchEvent.__init__
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent.Type`
            device: :sip:ref:`~PyQt5.QtGui.QTouchDevice` = None
            modifiers: Union[:sip:ref:`~PyQt5.QtCore.Qt.KeyboardModifiers`, :sip:ref:`~PyQt5.QtCore.Qt.KeyboardModifier`] = :sip:ref:`~PyQt5.QtCore.Qt.KeyboardModifier.NoModifier`
            touchPointStates: Union[:sip:ref:`~PyQt5.QtCore.Qt.TouchPointStates`, :sip:ref:`~PyQt5.QtCore.Qt.TouchPointState`] = Qt.TouchPointStates()
            touchPoints: Iterable[:sip:ref:`~PyQt5.QtGui.QTouchEvent.TouchPoint`] = []
        :description: QtGui/QTouchEvent-__init__-f-1.rst

    .. sip:method:: PyQt5.QtGui.QTouchEvent.device
        :returns:
            :sip:ref:`~PyQt5.QtGui.QTouchDevice`
        :description: QtGui/QTouchEvent-device-f.rst

    .. sip:method:: PyQt5.QtGui.QTouchEvent.setDevice
        :args:
            :sip:ref:`~PyQt5.QtGui.QTouchDevice`
        :description: QtGui/QTouchEvent-setDevice-f.rst

    .. sip:method:: PyQt5.QtGui.QTouchEvent.target
        :returns:
            :sip:ref:`~PyQt5.QtCore.QObject`
        :description: QtGui/QTouchEvent-target-f.rst

    .. sip:method:: PyQt5.QtGui.QTouchEvent.touchPoints
        :returns:
            List[:sip:ref:`~PyQt5.QtGui.QTouchEvent.TouchPoint`]
        :description: QtGui/QTouchEvent-touchPoints-f.rst

    .. sip:method:: PyQt5.QtGui.QTouchEvent.touchPointStates
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.TouchPointStates`
        :description: QtGui/QTouchEvent-touchPointStates-f.rst

    .. sip:method:: PyQt5.QtGui.QTouchEvent.window
        :returns:
            :sip:ref:`~PyQt5.QtGui.QWindow`
        :description: QtGui/QTouchEvent-window-f.rst
