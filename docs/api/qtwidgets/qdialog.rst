:orphan:

.. sip:class:: PyQt5.QtWidgets.QDialog
    :inherits: :sip:ref:`~PyQt5.QtWidgets.QWidget`
    :description: QtWidgets/QDialog-c.rst

    .. sip:enum:: PyQt5.QtWidgets.QDialog.DialogCode
        :description: QtWidgets/QDialog-DialogCode-e.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QDialog.DialogCode.Accepted
            :description: QtWidgets/QDialog-DialogCode-Accepted-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QDialog.DialogCode.Rejected
            :description: QtWidgets/QDialog-DialogCode-Rejected-v.rst

    .. sip:method:: PyQt5.QtWidgets.QDialog.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
            flags: Union[:sip:ref:`~PyQt5.QtCore.Qt.WindowFlags`, :sip:ref:`~PyQt5.QtCore.Qt.WindowType`] = Qt.WindowFlags()
        :description: QtWidgets/QDialog-__init__-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDialog.accept
        :description: QtWidgets/QDialog-accept-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDialog.closeEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QCloseEvent`
        :description: QtWidgets/QDialog-closeEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDialog.contextMenuEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QContextMenuEvent`
        :description: QtWidgets/QDialog-contextMenuEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDialog.done
        :args:
            int
        :description: QtWidgets/QDialog-done-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDialog.eventFilter
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtWidgets/QDialog-eventFilter-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDialog.exec
        :returns:
            int
        :description: QtWidgets/QDialog-exec-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDialog.exec_
        :returns:
            int
        :description: QtWidgets/QDialog-exec_-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDialog.isSizeGripEnabled
        :returns:
            bool
        :description: QtWidgets/QDialog-isSizeGripEnabled-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDialog.keyPressEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QKeyEvent`
        :description: QtWidgets/QDialog-keyPressEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDialog.minimumSizeHint
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtWidgets/QDialog-minimumSizeHint-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDialog.open
        :description: QtWidgets/QDialog-open-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDialog.reject
        :description: QtWidgets/QDialog-reject-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDialog.resizeEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QResizeEvent`
        :description: QtWidgets/QDialog-resizeEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDialog.result
        :returns:
            int
        :description: QtWidgets/QDialog-result-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDialog.setModal
        :args:
            bool
        :description: QtWidgets/QDialog-setModal-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDialog.setResult
        :args:
            int
        :description: QtWidgets/QDialog-setResult-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDialog.setSizeGripEnabled
        :args:
            bool
        :description: QtWidgets/QDialog-setSizeGripEnabled-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDialog.setVisible
        :args:
            bool
        :description: QtWidgets/QDialog-setVisible-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDialog.showEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QShowEvent`
        :description: QtWidgets/QDialog-showEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDialog.sizeHint
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtWidgets/QDialog-sizeHint-f.rst

    .. sip:signal:: PyQt5.QtWidgets.QDialog.accepted
        :description: QtWidgets/QDialog-accepted-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QDialog.finished
        :args:
            int
        :description: QtWidgets/QDialog-finished-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QDialog.rejected
        :description: QtWidgets/QDialog-rejected-s.rst
