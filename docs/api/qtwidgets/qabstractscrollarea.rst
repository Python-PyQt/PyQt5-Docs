:orphan:

.. sip:class:: PyQt5.QtWidgets.QAbstractScrollArea
    :inherits: :sip:ref:`~PyQt5.QtWidgets.QFrame`
    :description: QtWidgets/QAbstractScrollArea-c.rst

    .. sip:enum:: PyQt5.QtWidgets.QAbstractScrollArea.SizeAdjustPolicy
        :description: QtWidgets/QAbstractScrollArea-SizeAdjustPolicy-e.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QAbstractScrollArea.SizeAdjustPolicy.AdjustIgnored
            :description: QtWidgets/QAbstractScrollArea-SizeAdjustPolicy-AdjustIgnored-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QAbstractScrollArea.SizeAdjustPolicy.AdjustToContents
            :description: QtWidgets/QAbstractScrollArea-SizeAdjustPolicy-AdjustToContents-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QAbstractScrollArea.SizeAdjustPolicy.AdjustToContentsOnFirstShow
            :description: QtWidgets/QAbstractScrollArea-SizeAdjustPolicy-AdjustToContentsOnFirstShow-v.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
        :description: QtWidgets/QAbstractScrollArea-__init__-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.addScrollBarWidget
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
            Union[:sip:ref:`~PyQt5.QtCore.Qt.Alignment`, :sip:ref:`~PyQt5.QtCore.Qt.AlignmentFlag`]
        :description: QtWidgets/QAbstractScrollArea-addScrollBarWidget-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.contextMenuEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QContextMenuEvent`
        :description: QtWidgets/QAbstractScrollArea-contextMenuEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.cornerWidget
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :description: QtWidgets/QAbstractScrollArea-cornerWidget-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.dragEnterEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QDragEnterEvent`
        :description: QtWidgets/QAbstractScrollArea-dragEnterEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.dragLeaveEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QDragLeaveEvent`
        :description: QtWidgets/QAbstractScrollArea-dragLeaveEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.dragMoveEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QDragMoveEvent`
        :description: QtWidgets/QAbstractScrollArea-dragMoveEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.dropEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QDropEvent`
        :description: QtWidgets/QAbstractScrollArea-dropEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.event
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtWidgets/QAbstractScrollArea-event-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.eventFilter
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtWidgets/QAbstractScrollArea-eventFilter-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.horizontalScrollBar
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QScrollBar`
        :description: QtWidgets/QAbstractScrollArea-horizontalScrollBar-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.horizontalScrollBarPolicy
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.ScrollBarPolicy`
        :description: QtWidgets/QAbstractScrollArea-horizontalScrollBarPolicy-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.keyPressEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QKeyEvent`
        :description: QtWidgets/QAbstractScrollArea-keyPressEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.maximumViewportSize
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtWidgets/QAbstractScrollArea-maximumViewportSize-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.minimumSizeHint
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtWidgets/QAbstractScrollArea-minimumSizeHint-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.mouseDoubleClickEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QMouseEvent`
        :description: QtWidgets/QAbstractScrollArea-mouseDoubleClickEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.mouseMoveEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QMouseEvent`
        :description: QtWidgets/QAbstractScrollArea-mouseMoveEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.mousePressEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QMouseEvent`
        :description: QtWidgets/QAbstractScrollArea-mousePressEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.mouseReleaseEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QMouseEvent`
        :description: QtWidgets/QAbstractScrollArea-mouseReleaseEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.paintEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QPaintEvent`
        :description: QtWidgets/QAbstractScrollArea-paintEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.resizeEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QResizeEvent`
        :description: QtWidgets/QAbstractScrollArea-resizeEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.scrollBarWidgets
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.Qt.Alignment`, :sip:ref:`~PyQt5.QtCore.Qt.AlignmentFlag`]
        :returns:
            List[:sip:ref:`~PyQt5.QtWidgets.QWidget`]
        :description: QtWidgets/QAbstractScrollArea-scrollBarWidgets-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.scrollContentsBy
        :args:
            int
            int
        :description: QtWidgets/QAbstractScrollArea-scrollContentsBy-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.setCornerWidget
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :description: QtWidgets/QAbstractScrollArea-setCornerWidget-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.setHorizontalScrollBar
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QScrollBar`
        :description: QtWidgets/QAbstractScrollArea-setHorizontalScrollBar-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.setHorizontalScrollBarPolicy
        :args:
            :sip:ref:`~PyQt5.QtCore.Qt.ScrollBarPolicy`
        :description: QtWidgets/QAbstractScrollArea-setHorizontalScrollBarPolicy-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.setSizeAdjustPolicy
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QAbstractScrollArea.SizeAdjustPolicy`
        :description: QtWidgets/QAbstractScrollArea-setSizeAdjustPolicy-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.setupViewport
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :description: QtWidgets/QAbstractScrollArea-setupViewport-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.setVerticalScrollBar
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QScrollBar`
        :description: QtWidgets/QAbstractScrollArea-setVerticalScrollBar-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.setVerticalScrollBarPolicy
        :args:
            :sip:ref:`~PyQt5.QtCore.Qt.ScrollBarPolicy`
        :description: QtWidgets/QAbstractScrollArea-setVerticalScrollBarPolicy-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.setViewport
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :description: QtWidgets/QAbstractScrollArea-setViewport-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.setViewportMargins
        :args:
            :sip:ref:`~PyQt5.QtCore.QMargins`
        :description: QtWidgets/QAbstractScrollArea-setViewportMargins-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.setViewportMargins
        :args:
            int
            int
            int
            int
        :description: QtWidgets/QAbstractScrollArea-setViewportMargins-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.sizeAdjustPolicy
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAbstractScrollArea.SizeAdjustPolicy`
        :description: QtWidgets/QAbstractScrollArea-sizeAdjustPolicy-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.sizeHint
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtWidgets/QAbstractScrollArea-sizeHint-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.verticalScrollBar
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QScrollBar`
        :description: QtWidgets/QAbstractScrollArea-verticalScrollBar-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.verticalScrollBarPolicy
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.ScrollBarPolicy`
        :description: QtWidgets/QAbstractScrollArea-verticalScrollBarPolicy-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.viewport
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :description: QtWidgets/QAbstractScrollArea-viewport-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.viewportEvent
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtWidgets/QAbstractScrollArea-viewportEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.viewportMargins
        :returns:
            :sip:ref:`~PyQt5.QtCore.QMargins`
        :description: QtWidgets/QAbstractScrollArea-viewportMargins-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.viewportSizeHint
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtWidgets/QAbstractScrollArea-viewportSizeHint-f.rst

    .. sip:method:: PyQt5.QtWidgets.QAbstractScrollArea.wheelEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QWheelEvent`
        :description: QtWidgets/QAbstractScrollArea-wheelEvent-f.rst
