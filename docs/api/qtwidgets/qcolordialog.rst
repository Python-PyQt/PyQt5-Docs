:orphan:

.. sip:class:: PyQt5.QtWidgets.QColorDialog
    :inherits: :sip:ref:`~PyQt5.QtWidgets.QDialog`
    :description: QtWidgets/QColorDialog-c.rst

    .. sip:enum:: PyQt5.QtWidgets.QColorDialog.ColorDialogOption
        :description: QtWidgets/QColorDialog-ColorDialogOption-e.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QColorDialog.ColorDialogOption.DontUseNativeDialog
            :description: QtWidgets/QColorDialog-ColorDialogOption-DontUseNativeDialog-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QColorDialog.ColorDialogOption.NoButtons
            :description: QtWidgets/QColorDialog-ColorDialogOption-NoButtons-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QColorDialog.ColorDialogOption.ShowAlphaChannel
            :description: QtWidgets/QColorDialog-ColorDialogOption-ShowAlphaChannel-v.rst

    .. sip:method:: PyQt5.QtWidgets.QColorDialog.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
        :description: QtWidgets/QColorDialog-__init__-f.rst

    .. sip:method:: PyQt5.QtWidgets.QColorDialog.__init__
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`]
            parent: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
        :description: QtWidgets/QColorDialog-__init__-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QColorDialog.changeEvent
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :description: QtWidgets/QColorDialog-changeEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QColorDialog.currentColor
        :returns:
            :sip:ref:`~PyQt5.QtGui.QColor`
        :description: QtWidgets/QColorDialog-currentColor-f.rst

    .. sip:method:: PyQt5.QtWidgets.QColorDialog.customColor
        :args:
            int
        :returns:
            :sip:ref:`~PyQt5.QtGui.QColor`
        :static:
        :description: QtWidgets/QColorDialog-customColor-f.rst

    .. sip:method:: PyQt5.QtWidgets.QColorDialog.customCount
        :returns:
            int
        :static:
        :description: QtWidgets/QColorDialog-customCount-f.rst

    .. sip:method:: PyQt5.QtWidgets.QColorDialog.done
        :args:
            int
        :description: QtWidgets/QColorDialog-done-f.rst

    .. sip:method:: PyQt5.QtWidgets.QColorDialog.getColor
        :args:
            initial: Union[:sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`] = :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor.white`
            parent: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
            title: str = ''
            options: Union[:sip:ref:`~PyQt5.QtWidgets.QColorDialog.ColorDialogOptions`, :sip:ref:`~PyQt5.QtWidgets.QColorDialog.ColorDialogOption`] = QColorDialog.ColorDialogOptions()
        :returns:
            :sip:ref:`~PyQt5.QtGui.QColor`
        :static:
        :description: QtWidgets/QColorDialog-getColor-f.rst

    .. sip:method:: PyQt5.QtWidgets.QColorDialog.open
        :description: QtWidgets/QColorDialog-open-f.rst

    .. sip:method:: PyQt5.QtWidgets.QColorDialog.open
        :args:
            PYQT_SLOT
        :description: QtWidgets/QColorDialog-open-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QColorDialog.options
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QColorDialog.ColorDialogOptions`
        :description: QtWidgets/QColorDialog-options-f.rst

    .. sip:method:: PyQt5.QtWidgets.QColorDialog.selectedColor
        :returns:
            :sip:ref:`~PyQt5.QtGui.QColor`
        :description: QtWidgets/QColorDialog-selectedColor-f.rst

    .. sip:method:: PyQt5.QtWidgets.QColorDialog.setCurrentColor
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`]
        :description: QtWidgets/QColorDialog-setCurrentColor-f.rst

    .. sip:method:: PyQt5.QtWidgets.QColorDialog.setCustomColor
        :args:
            int
            Union[:sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`]
        :static:
        :description: QtWidgets/QColorDialog-setCustomColor-f.rst

    .. sip:method:: PyQt5.QtWidgets.QColorDialog.setOption
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QColorDialog.ColorDialogOption`
            on: bool = True
        :description: QtWidgets/QColorDialog-setOption-f.rst

    .. sip:method:: PyQt5.QtWidgets.QColorDialog.setOptions
        :args:
            Union[:sip:ref:`~PyQt5.QtWidgets.QColorDialog.ColorDialogOptions`, :sip:ref:`~PyQt5.QtWidgets.QColorDialog.ColorDialogOption`]
        :description: QtWidgets/QColorDialog-setOptions-f.rst

    .. sip:method:: PyQt5.QtWidgets.QColorDialog.setStandardColor
        :args:
            int
            Union[:sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`]
        :static:
        :description: QtWidgets/QColorDialog-setStandardColor-f.rst

    .. sip:method:: PyQt5.QtWidgets.QColorDialog.setVisible
        :args:
            bool
        :description: QtWidgets/QColorDialog-setVisible-f.rst

    .. sip:method:: PyQt5.QtWidgets.QColorDialog.standardColor
        :args:
            int
        :returns:
            :sip:ref:`~PyQt5.QtGui.QColor`
        :static:
        :description: QtWidgets/QColorDialog-standardColor-f.rst

    .. sip:method:: PyQt5.QtWidgets.QColorDialog.testOption
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QColorDialog.ColorDialogOption`
        :returns:
            bool
        :description: QtWidgets/QColorDialog-testOption-f.rst

    .. sip:signal:: PyQt5.QtWidgets.QColorDialog.colorSelected
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`]
        :description: QtWidgets/QColorDialog-colorSelected-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QColorDialog.currentColorChanged
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`]
        :description: QtWidgets/QColorDialog-currentColorChanged-s.rst
