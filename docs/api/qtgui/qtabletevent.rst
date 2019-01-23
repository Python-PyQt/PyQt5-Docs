:orphan:

.. sip:class:: PyQt5.QtGui.QTabletEvent
    :inherits: :sip:ref:`~PyQt5.QtGui.QInputEvent`
    :description: QtGui/QTabletEvent-c.rst

    .. sip:enum:: PyQt5.QtGui.QTabletEvent.PointerType
        :description: QtGui/QTabletEvent-PointerType-e.rst

        .. sip:enum-member:: PyQt5.QtGui.QTabletEvent.PointerType.Cursor
            :description: QtGui/QTabletEvent-PointerType-Cursor-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QTabletEvent.PointerType.Eraser
            :description: QtGui/QTabletEvent-PointerType-Eraser-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QTabletEvent.PointerType.Pen
            :description: QtGui/QTabletEvent-PointerType-Pen-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QTabletEvent.PointerType.UnknownPointer
            :description: QtGui/QTabletEvent-PointerType-UnknownPointer-v.rst

    .. sip:enum:: PyQt5.QtGui.QTabletEvent.TabletDevice
        :description: QtGui/QTabletEvent-TabletDevice-e.rst

        .. sip:enum-member:: PyQt5.QtGui.QTabletEvent.TabletDevice.Airbrush
            :description: QtGui/QTabletEvent-TabletDevice-Airbrush-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QTabletEvent.TabletDevice.FourDMouse
            :description: QtGui/QTabletEvent-TabletDevice-FourDMouse-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QTabletEvent.TabletDevice.NoDevice
            :description: QtGui/QTabletEvent-TabletDevice-NoDevice-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QTabletEvent.TabletDevice.Puck
            :description: QtGui/QTabletEvent-TabletDevice-Puck-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QTabletEvent.TabletDevice.RotationStylus
            :description: QtGui/QTabletEvent-TabletDevice-RotationStylus-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QTabletEvent.TabletDevice.Stylus
            :description: QtGui/QTabletEvent-TabletDevice-Stylus-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QTabletEvent.TabletDevice.XFreeEraser
            :description: QtGui/QTabletEvent-TabletDevice-XFreeEraser-v.rst

    .. sip:method:: PyQt5.QtGui.QTabletEvent.__init__
        :args:
            :sip:ref:`~PyQt5.QtGui.QTabletEvent`
        :description: QtGui/QTabletEvent-__init__-f.rst

    .. sip:method:: PyQt5.QtGui.QTabletEvent.__init__
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent.Type`
            Union[:sip:ref:`~PyQt5.QtCore.QPointF`, :sip:ref:`~PyQt5.QtCore.QPoint`]
            Union[:sip:ref:`~PyQt5.QtCore.QPointF`, :sip:ref:`~PyQt5.QtCore.QPoint`]
            int
            int
            float
            int
            int
            float
            float
            int
            Union[:sip:ref:`~PyQt5.QtCore.Qt.KeyboardModifiers`, :sip:ref:`~PyQt5.QtCore.Qt.KeyboardModifier`]
            int
        :description: QtGui/QTabletEvent-__init__-f-1.rst

    .. sip:method:: PyQt5.QtGui.QTabletEvent.__init__
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent.Type`
            Union[:sip:ref:`~PyQt5.QtCore.QPointF`, :sip:ref:`~PyQt5.QtCore.QPoint`]
            Union[:sip:ref:`~PyQt5.QtCore.QPointF`, :sip:ref:`~PyQt5.QtCore.QPoint`]
            int
            int
            float
            int
            int
            float
            float
            int
            Union[:sip:ref:`~PyQt5.QtCore.Qt.KeyboardModifiers`, :sip:ref:`~PyQt5.QtCore.Qt.KeyboardModifier`]
            int
            :sip:ref:`~PyQt5.QtCore.Qt.MouseButton`
            Union[:sip:ref:`~PyQt5.QtCore.Qt.MouseButtons`, :sip:ref:`~PyQt5.QtCore.Qt.MouseButton`]
        :description: QtGui/QTabletEvent-__init__-f-2.rst

    .. sip:method:: PyQt5.QtGui.QTabletEvent.button
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.MouseButton`
        :description: QtGui/QTabletEvent-button-f.rst

    .. sip:method:: PyQt5.QtGui.QTabletEvent.buttons
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.MouseButtons`
        :description: QtGui/QTabletEvent-buttons-f.rst

    .. sip:method:: PyQt5.QtGui.QTabletEvent.device
        :returns:
            :sip:ref:`~PyQt5.QtGui.QTabletEvent.TabletDevice`
        :description: QtGui/QTabletEvent-device-f.rst

    .. sip:method:: PyQt5.QtGui.QTabletEvent.globalPos
        :returns:
            :sip:ref:`~PyQt5.QtCore.QPoint`
        :description: QtGui/QTabletEvent-globalPos-f.rst

    .. sip:method:: PyQt5.QtGui.QTabletEvent.globalPosF
        :returns:
            :sip:ref:`~PyQt5.QtCore.QPointF`
        :description: QtGui/QTabletEvent-globalPosF-f.rst

    .. sip:method:: PyQt5.QtGui.QTabletEvent.globalX
        :returns:
            int
        :description: QtGui/QTabletEvent-globalX-f.rst

    .. sip:method:: PyQt5.QtGui.QTabletEvent.globalY
        :returns:
            int
        :description: QtGui/QTabletEvent-globalY-f.rst

    .. sip:method:: PyQt5.QtGui.QTabletEvent.hiResGlobalX
        :returns:
            float
        :description: QtGui/QTabletEvent-hiResGlobalX-f.rst

    .. sip:method:: PyQt5.QtGui.QTabletEvent.hiResGlobalY
        :returns:
            float
        :description: QtGui/QTabletEvent-hiResGlobalY-f.rst

    .. sip:method:: PyQt5.QtGui.QTabletEvent.pointerType
        :returns:
            :sip:ref:`~PyQt5.QtGui.QTabletEvent.PointerType`
        :description: QtGui/QTabletEvent-pointerType-f.rst

    .. sip:method:: PyQt5.QtGui.QTabletEvent.pos
        :returns:
            :sip:ref:`~PyQt5.QtCore.QPoint`
        :description: QtGui/QTabletEvent-pos-f.rst

    .. sip:method:: PyQt5.QtGui.QTabletEvent.posF
        :returns:
            :sip:ref:`~PyQt5.QtCore.QPointF`
        :description: QtGui/QTabletEvent-posF-f.rst

    .. sip:method:: PyQt5.QtGui.QTabletEvent.pressure
        :returns:
            float
        :description: QtGui/QTabletEvent-pressure-f.rst

    .. sip:method:: PyQt5.QtGui.QTabletEvent.rotation
        :returns:
            float
        :description: QtGui/QTabletEvent-rotation-f.rst

    .. sip:method:: PyQt5.QtGui.QTabletEvent.tangentialPressure
        :returns:
            float
        :description: QtGui/QTabletEvent-tangentialPressure-f.rst

    .. sip:method:: PyQt5.QtGui.QTabletEvent.uniqueId
        :returns:
            int
        :description: QtGui/QTabletEvent-uniqueId-f.rst

    .. sip:method:: PyQt5.QtGui.QTabletEvent.x
        :returns:
            int
        :description: QtGui/QTabletEvent-x-f.rst

    .. sip:method:: PyQt5.QtGui.QTabletEvent.xTilt
        :returns:
            int
        :description: QtGui/QTabletEvent-xTilt-f.rst

    .. sip:method:: PyQt5.QtGui.QTabletEvent.y
        :returns:
            int
        :description: QtGui/QTabletEvent-y-f.rst

    .. sip:method:: PyQt5.QtGui.QTabletEvent.yTilt
        :returns:
            int
        :description: QtGui/QTabletEvent-yTilt-f.rst

    .. sip:method:: PyQt5.QtGui.QTabletEvent.z
        :returns:
            int
        :description: QtGui/QTabletEvent-z-f.rst
