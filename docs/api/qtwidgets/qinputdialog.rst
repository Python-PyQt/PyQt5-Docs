:orphan:

.. sip:class:: PyQt5.QtWidgets.QInputDialog
    :inherits: :sip:ref:`~PyQt5.QtWidgets.QDialog`
    :description: QtWidgets/QInputDialog-c.rst

    .. sip:enum:: PyQt5.QtWidgets.QInputDialog.InputDialogOption
        :description: QtWidgets/QInputDialog-InputDialogOption-e.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QInputDialog.InputDialogOption.NoButtons
            :description: QtWidgets/QInputDialog-InputDialogOption-NoButtons-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QInputDialog.InputDialogOption.UseListViewForComboBoxItems
            :description: QtWidgets/QInputDialog-InputDialogOption-UseListViewForComboBoxItems-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QInputDialog.InputDialogOption.UsePlainTextEditForTextInput
            :description: QtWidgets/QInputDialog-InputDialogOption-UsePlainTextEditForTextInput-v.rst

    .. sip:enum:: PyQt5.QtWidgets.QInputDialog.InputMode
        :description: QtWidgets/QInputDialog-InputMode-e.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QInputDialog.InputMode.DoubleInput
            :description: QtWidgets/QInputDialog-InputMode-DoubleInput-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QInputDialog.InputMode.IntInput
            :description: QtWidgets/QInputDialog-InputMode-IntInput-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QInputDialog.InputMode.TextInput
            :description: QtWidgets/QInputDialog-InputMode-TextInput-v.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
            flags: Union[:sip:ref:`~PyQt5.QtCore.Qt.WindowFlags`, :sip:ref:`~PyQt5.QtCore.Qt.WindowType`] = Qt.WindowFlags()
        :description: QtWidgets/QInputDialog-__init__-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.cancelButtonText
        :returns:
            str
        :description: QtWidgets/QInputDialog-cancelButtonText-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.comboBoxItems
        :returns:
            List[str]
        :description: QtWidgets/QInputDialog-comboBoxItems-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.done
        :args:
            int
        :description: QtWidgets/QInputDialog-done-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.doubleDecimals
        :returns:
            int
        :description: QtWidgets/QInputDialog-doubleDecimals-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.doubleMaximum
        :returns:
            float
        :description: QtWidgets/QInputDialog-doubleMaximum-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.doubleMinimum
        :returns:
            float
        :description: QtWidgets/QInputDialog-doubleMinimum-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.doubleStep
        :returns:
            float
        :description: QtWidgets/QInputDialog-doubleStep-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.doubleValue
        :returns:
            float
        :description: QtWidgets/QInputDialog-doubleValue-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.getDouble
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
            str
            str
            value: float = 0
            min: float = -2147483647
            max: float = 2147483647
            decimals: int = 1
            flags: Union[:sip:ref:`~PyQt5.QtCore.Qt.WindowFlags`, :sip:ref:`~PyQt5.QtCore.Qt.WindowType`] = Qt.WindowFlags()
        :returns:
            float
            bool
        :static:
        :description: QtWidgets/QInputDialog-getDouble-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.getDouble
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
            str
            str
            float
            float
            float
            int
            Union[:sip:ref:`~PyQt5.QtCore.Qt.WindowFlags`, :sip:ref:`~PyQt5.QtCore.Qt.WindowType`]
            float
        :returns:
            float
            bool
        :static:
        :description: QtWidgets/QInputDialog-getDouble-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.getInt
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
            str
            str
            value: int = 0
            min: int = -2147483647
            max: int = 2147483647
            step: int = 1
            flags: Union[:sip:ref:`~PyQt5.QtCore.Qt.WindowFlags`, :sip:ref:`~PyQt5.QtCore.Qt.WindowType`] = Qt.WindowFlags()
        :returns:
            int
            bool
        :static:
        :description: QtWidgets/QInputDialog-getInt-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.getItem
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
            str
            str
            Iterable[str]
            current: int = 0
            editable: bool = True
            flags: Union[:sip:ref:`~PyQt5.QtCore.Qt.WindowFlags`, :sip:ref:`~PyQt5.QtCore.Qt.WindowType`] = Qt.WindowFlags()
            inputMethodHints: Union[:sip:ref:`~PyQt5.QtCore.Qt.InputMethodHints`, :sip:ref:`~PyQt5.QtCore.Qt.InputMethodHint`] = :sip:ref:`~PyQt5.QtCore.Qt.InputMethodHint.ImhNone`
        :returns:
            str
            bool
        :static:
        :description: QtWidgets/QInputDialog-getItem-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.getMultiLineText
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
            str
            str
            text: str = ''
            flags: Union[:sip:ref:`~PyQt5.QtCore.Qt.WindowFlags`, :sip:ref:`~PyQt5.QtCore.Qt.WindowType`] = Qt.WindowFlags()
            inputMethodHints: Union[:sip:ref:`~PyQt5.QtCore.Qt.InputMethodHints`, :sip:ref:`~PyQt5.QtCore.Qt.InputMethodHint`] = :sip:ref:`~PyQt5.QtCore.Qt.InputMethodHint.ImhNone`
        :returns:
            str
            bool
        :static:
        :description: QtWidgets/QInputDialog-getMultiLineText-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.getText
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
            str
            str
            echo: :sip:ref:`~PyQt5.QtWidgets.QLineEdit.EchoMode` = :sip:ref:`~PyQt5.QtWidgets.QLineEdit.EchoMode.Normal`
            text: str = ''
            flags: Union[:sip:ref:`~PyQt5.QtCore.Qt.WindowFlags`, :sip:ref:`~PyQt5.QtCore.Qt.WindowType`] = Qt.WindowFlags()
            inputMethodHints: Union[:sip:ref:`~PyQt5.QtCore.Qt.InputMethodHints`, :sip:ref:`~PyQt5.QtCore.Qt.InputMethodHint`] = :sip:ref:`~PyQt5.QtCore.Qt.InputMethodHint.ImhNone`
        :returns:
            str
            bool
        :static:
        :description: QtWidgets/QInputDialog-getText-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.inputMode
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QInputDialog.InputMode`
        :description: QtWidgets/QInputDialog-inputMode-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.intMaximum
        :returns:
            int
        :description: QtWidgets/QInputDialog-intMaximum-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.intMinimum
        :returns:
            int
        :description: QtWidgets/QInputDialog-intMinimum-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.intStep
        :returns:
            int
        :description: QtWidgets/QInputDialog-intStep-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.intValue
        :returns:
            int
        :description: QtWidgets/QInputDialog-intValue-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.isComboBoxEditable
        :returns:
            bool
        :description: QtWidgets/QInputDialog-isComboBoxEditable-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.labelText
        :returns:
            str
        :description: QtWidgets/QInputDialog-labelText-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.minimumSizeHint
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtWidgets/QInputDialog-minimumSizeHint-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.okButtonText
        :returns:
            str
        :description: QtWidgets/QInputDialog-okButtonText-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.open
        :description: QtWidgets/QInputDialog-open-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.open
        :args:
            PYQT_SLOT
        :description: QtWidgets/QInputDialog-open-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.options
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QInputDialog.InputDialogOptions`
        :description: QtWidgets/QInputDialog-options-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.setCancelButtonText
        :args:
            str
        :description: QtWidgets/QInputDialog-setCancelButtonText-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.setComboBoxEditable
        :args:
            bool
        :description: QtWidgets/QInputDialog-setComboBoxEditable-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.setComboBoxItems
        :args:
            Iterable[str]
        :description: QtWidgets/QInputDialog-setComboBoxItems-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.setDoubleDecimals
        :args:
            int
        :description: QtWidgets/QInputDialog-setDoubleDecimals-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.setDoubleMaximum
        :args:
            float
        :description: QtWidgets/QInputDialog-setDoubleMaximum-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.setDoubleMinimum
        :args:
            float
        :description: QtWidgets/QInputDialog-setDoubleMinimum-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.setDoubleRange
        :args:
            float
            float
        :description: QtWidgets/QInputDialog-setDoubleRange-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.setDoubleStep
        :args:
            float
        :description: QtWidgets/QInputDialog-setDoubleStep-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.setDoubleValue
        :args:
            float
        :description: QtWidgets/QInputDialog-setDoubleValue-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.setInputMode
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QInputDialog.InputMode`
        :description: QtWidgets/QInputDialog-setInputMode-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.setIntMaximum
        :args:
            int
        :description: QtWidgets/QInputDialog-setIntMaximum-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.setIntMinimum
        :args:
            int
        :description: QtWidgets/QInputDialog-setIntMinimum-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.setIntRange
        :args:
            int
            int
        :description: QtWidgets/QInputDialog-setIntRange-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.setIntStep
        :args:
            int
        :description: QtWidgets/QInputDialog-setIntStep-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.setIntValue
        :args:
            int
        :description: QtWidgets/QInputDialog-setIntValue-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.setLabelText
        :args:
            str
        :description: QtWidgets/QInputDialog-setLabelText-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.setOkButtonText
        :args:
            str
        :description: QtWidgets/QInputDialog-setOkButtonText-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.setOption
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QInputDialog.InputDialogOption`
            on: bool = True
        :description: QtWidgets/QInputDialog-setOption-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.setOptions
        :args:
            Union[:sip:ref:`~PyQt5.QtWidgets.QInputDialog.InputDialogOptions`, :sip:ref:`~PyQt5.QtWidgets.QInputDialog.InputDialogOption`]
        :description: QtWidgets/QInputDialog-setOptions-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.setTextEchoMode
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QLineEdit.EchoMode`
        :description: QtWidgets/QInputDialog-setTextEchoMode-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.setTextValue
        :args:
            str
        :description: QtWidgets/QInputDialog-setTextValue-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.setVisible
        :args:
            bool
        :description: QtWidgets/QInputDialog-setVisible-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.sizeHint
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtWidgets/QInputDialog-sizeHint-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.testOption
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QInputDialog.InputDialogOption`
        :returns:
            bool
        :description: QtWidgets/QInputDialog-testOption-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.textEchoMode
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QLineEdit.EchoMode`
        :description: QtWidgets/QInputDialog-textEchoMode-f.rst

    .. sip:method:: PyQt5.QtWidgets.QInputDialog.textValue
        :returns:
            str
        :description: QtWidgets/QInputDialog-textValue-f.rst

    .. sip:signal:: PyQt5.QtWidgets.QInputDialog.doubleValueChanged
        :args:
            float
        :description: QtWidgets/QInputDialog-doubleValueChanged-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QInputDialog.doubleValueSelected
        :args:
            float
        :description: QtWidgets/QInputDialog-doubleValueSelected-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QInputDialog.intValueChanged
        :args:
            int
        :description: QtWidgets/QInputDialog-intValueChanged-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QInputDialog.intValueSelected
        :args:
            int
        :description: QtWidgets/QInputDialog-intValueSelected-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QInputDialog.textValueChanged
        :args:
            str
        :description: QtWidgets/QInputDialog-textValueChanged-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QInputDialog.textValueSelected
        :args:
            str
        :description: QtWidgets/QInputDialog-textValueSelected-s.rst
