:orphan:

.. sip:class:: PyQt5.QtWidgets.QGraphicsEffect
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtWidgets/QGraphicsEffect-c.rst

    .. sip:enum:: PyQt5.QtWidgets.QGraphicsEffect.ChangeFlag
        :description: QtWidgets/QGraphicsEffect-ChangeFlag-e.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QGraphicsEffect.ChangeFlag.SourceAttached
            :description: QtWidgets/QGraphicsEffect-ChangeFlag-SourceAttached-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QGraphicsEffect.ChangeFlag.SourceBoundingRectChanged
            :description: QtWidgets/QGraphicsEffect-ChangeFlag-SourceBoundingRectChanged-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QGraphicsEffect.ChangeFlag.SourceDetached
            :description: QtWidgets/QGraphicsEffect-ChangeFlag-SourceDetached-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QGraphicsEffect.ChangeFlag.SourceInvalidated
            :description: QtWidgets/QGraphicsEffect-ChangeFlag-SourceInvalidated-v.rst

    .. sip:enum:: PyQt5.QtWidgets.QGraphicsEffect.PixmapPadMode
        :description: QtWidgets/QGraphicsEffect-PixmapPadMode-e.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QGraphicsEffect.PixmapPadMode.NoPad
            :description: QtWidgets/QGraphicsEffect-PixmapPadMode-NoPad-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QGraphicsEffect.PixmapPadMode.PadToEffectiveBoundingRect
            :description: QtWidgets/QGraphicsEffect-PixmapPadMode-PadToEffectiveBoundingRect-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QGraphicsEffect.PixmapPadMode.PadToTransparentBorder
            :description: QtWidgets/QGraphicsEffect-PixmapPadMode-PadToTransparentBorder-v.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsEffect.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtWidgets/QGraphicsEffect-__init__-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsEffect.boundingRect
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRectF`
        :description: QtWidgets/QGraphicsEffect-boundingRect-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsEffect.boundingRectFor
        :args:
            :sip:ref:`~PyQt5.QtCore.QRectF`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRectF`
        :description: QtWidgets/QGraphicsEffect-boundingRectFor-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsEffect.draw
        :args:
            :sip:ref:`~PyQt5.QtGui.QPainter`
        :description: QtWidgets/QGraphicsEffect-draw-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsEffect.drawSource
        :args:
            :sip:ref:`~PyQt5.QtGui.QPainter`
        :description: QtWidgets/QGraphicsEffect-drawSource-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsEffect.isEnabled
        :returns:
            bool
        :description: QtWidgets/QGraphicsEffect-isEnabled-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsEffect.setEnabled
        :args:
            bool
        :description: QtWidgets/QGraphicsEffect-setEnabled-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsEffect.sourceBoundingRect
        :args:
            system: :sip:ref:`~PyQt5.QtCore.Qt.CoordinateSystem` = :sip:ref:`~PyQt5.QtCore.Qt.CoordinateSystem.LogicalCoordinates`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRectF`
        :description: QtWidgets/QGraphicsEffect-sourceBoundingRect-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsEffect.sourceChanged
        :args:
            Union[:sip:ref:`~PyQt5.QtWidgets.QGraphicsEffect.ChangeFlags`, :sip:ref:`~PyQt5.QtWidgets.QGraphicsEffect.ChangeFlag`]
        :description: QtWidgets/QGraphicsEffect-sourceChanged-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsEffect.sourceIsPixmap
        :returns:
            bool
        :description: QtWidgets/QGraphicsEffect-sourceIsPixmap-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsEffect.sourcePixmap
        :args:
            system: :sip:ref:`~PyQt5.QtCore.Qt.CoordinateSystem` = :sip:ref:`~PyQt5.QtCore.Qt.CoordinateSystem.LogicalCoordinates`
            mode: :sip:ref:`~PyQt5.QtWidgets.QGraphicsEffect.PixmapPadMode` = :sip:ref:`~PyQt5.QtWidgets.QGraphicsEffect.PixmapPadMode.PadToEffectiveBoundingRect`
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPixmap`
            :sip:ref:`~PyQt5.QtCore.QPoint`
        :description: QtWidgets/QGraphicsEffect-sourcePixmap-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsEffect.update
        :description: QtWidgets/QGraphicsEffect-update-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsEffect.updateBoundingRect
        :description: QtWidgets/QGraphicsEffect-updateBoundingRect-f.rst

    .. sip:signal:: PyQt5.QtWidgets.QGraphicsEffect.enabledChanged
        :args:
            bool
        :description: QtWidgets/QGraphicsEffect-enabledChanged-s.rst
