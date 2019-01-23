:orphan:

.. sip:class:: PyQt5.QtWidgets.QMenuBar
    :inherits: :sip:ref:`~PyQt5.QtWidgets.QWidget`
    :description: QtWidgets/QMenuBar-c.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
        :description: QtWidgets/QMenuBar-__init__-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.actionAt
        :args:
            :sip:ref:`~PyQt5.QtCore.QPoint`
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenuBar-actionAt-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.actionEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QActionEvent`
        :description: QtWidgets/QMenuBar-actionEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.actionGeometry
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRect`
        :description: QtWidgets/QMenuBar-actionGeometry-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.activeAction
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenuBar-activeAction-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.addAction
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenuBar-addAction-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.addAction
        :args:
            str
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenuBar-addAction-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.addAction
        :args:
            str
            PYQT_SLOT
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenuBar-addAction-f-2.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.addMenu
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QMenu`
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenuBar-addMenu-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.addMenu
        :args:
            str
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QMenu`
        :description: QtWidgets/QMenuBar-addMenu-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.addMenu
        :args:
            :sip:ref:`~PyQt5.QtGui.QIcon`
            str
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QMenu`
        :description: QtWidgets/QMenuBar-addMenu-f-2.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.addSeparator
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenuBar-addSeparator-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.changeEvent
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :description: QtWidgets/QMenuBar-changeEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.clear
        :description: QtWidgets/QMenuBar-clear-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.cornerWidget
        :args:
            corner: :sip:ref:`~PyQt5.QtCore.Qt.Corner` = :sip:ref:`~PyQt5.QtCore.Qt.Corner.TopRightCorner`
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :description: QtWidgets/QMenuBar-cornerWidget-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.event
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtWidgets/QMenuBar-event-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.eventFilter
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtWidgets/QMenuBar-eventFilter-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.focusInEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QFocusEvent`
        :description: QtWidgets/QMenuBar-focusInEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.focusOutEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QFocusEvent`
        :description: QtWidgets/QMenuBar-focusOutEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.heightForWidth
        :args:
            int
        :returns:
            int
        :description: QtWidgets/QMenuBar-heightForWidth-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.initStyleOption
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QStyleOptionMenuItem`
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenuBar-initStyleOption-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.insertMenu
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
            :sip:ref:`~PyQt5.QtWidgets.QMenu`
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenuBar-insertMenu-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.insertSeparator
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenuBar-insertSeparator-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.isDefaultUp
        :returns:
            bool
        :description: QtWidgets/QMenuBar-isDefaultUp-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.isNativeMenuBar
        :returns:
            bool
        :description: QtWidgets/QMenuBar-isNativeMenuBar-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.keyPressEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QKeyEvent`
        :description: QtWidgets/QMenuBar-keyPressEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.leaveEvent
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :description: QtWidgets/QMenuBar-leaveEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.minimumSizeHint
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtWidgets/QMenuBar-minimumSizeHint-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.mouseMoveEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QMouseEvent`
        :description: QtWidgets/QMenuBar-mouseMoveEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.mousePressEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QMouseEvent`
        :description: QtWidgets/QMenuBar-mousePressEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.mouseReleaseEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QMouseEvent`
        :description: QtWidgets/QMenuBar-mouseReleaseEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.paintEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QPaintEvent`
        :description: QtWidgets/QMenuBar-paintEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.resizeEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QResizeEvent`
        :description: QtWidgets/QMenuBar-resizeEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.setActiveAction
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenuBar-setActiveAction-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.setCornerWidget
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
            corner: :sip:ref:`~PyQt5.QtCore.Qt.Corner` = :sip:ref:`~PyQt5.QtCore.Qt.Corner.TopRightCorner`
        :description: QtWidgets/QMenuBar-setCornerWidget-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.setDefaultUp
        :args:
            bool
        :description: QtWidgets/QMenuBar-setDefaultUp-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.setNativeMenuBar
        :args:
            bool
        :description: QtWidgets/QMenuBar-setNativeMenuBar-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.setVisible
        :args:
            bool
        :description: QtWidgets/QMenuBar-setVisible-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.sizeHint
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtWidgets/QMenuBar-sizeHint-f.rst

    .. sip:method:: PyQt5.QtWidgets.QMenuBar.timerEvent
        :args:
            :sip:ref:`~PyQt5.QtCore.QTimerEvent`
        :description: QtWidgets/QMenuBar-timerEvent-f.rst

    .. sip:signal:: PyQt5.QtWidgets.QMenuBar.hovered
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenuBar-hovered-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QMenuBar.triggered
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QMenuBar-triggered-s.rst
