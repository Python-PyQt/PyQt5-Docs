:orphan:

.. sip:class:: PyQt5.QtWidgets.QFontDialog
    :inherits: :sip:ref:`~PyQt5.QtWidgets.QDialog`
    :description: QtWidgets/QFontDialog-c.rst

    .. sip:enum:: PyQt5.QtWidgets.QFontDialog.FontDialogOption
        :description: QtWidgets/QFontDialog-FontDialogOption-e.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFontDialog.FontDialogOption.DontUseNativeDialog
            :description: QtWidgets/QFontDialog-FontDialogOption-DontUseNativeDialog-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFontDialog.FontDialogOption.MonospacedFonts
            :description: QtWidgets/QFontDialog-FontDialogOption-MonospacedFonts-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFontDialog.FontDialogOption.NoButtons
            :description: QtWidgets/QFontDialog-FontDialogOption-NoButtons-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFontDialog.FontDialogOption.NonScalableFonts
            :description: QtWidgets/QFontDialog-FontDialogOption-NonScalableFonts-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFontDialog.FontDialogOption.ProportionalFonts
            :description: QtWidgets/QFontDialog-FontDialogOption-ProportionalFonts-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFontDialog.FontDialogOption.ScalableFonts
            :description: QtWidgets/QFontDialog-FontDialogOption-ScalableFonts-v.rst

    .. sip:method:: PyQt5.QtWidgets.QFontDialog.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
        :description: QtWidgets/QFontDialog-__init__-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFontDialog.__init__
        :args:
            :sip:ref:`~PyQt5.QtGui.QFont`
            parent: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
        :description: QtWidgets/QFontDialog-__init__-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QFontDialog.changeEvent
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :description: QtWidgets/QFontDialog-changeEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFontDialog.currentFont
        :returns:
            :sip:ref:`~PyQt5.QtGui.QFont`
        :description: QtWidgets/QFontDialog-currentFont-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFontDialog.done
        :args:
            int
        :description: QtWidgets/QFontDialog-done-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFontDialog.eventFilter
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtWidgets/QFontDialog-eventFilter-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFontDialog.getFont
        :args:
            parent: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
        :returns:
            :sip:ref:`~PyQt5.QtGui.QFont`
            bool
        :static:
        :description: QtWidgets/QFontDialog-getFont-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFontDialog.getFont
        :args:
            :sip:ref:`~PyQt5.QtGui.QFont`
            parent: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
            caption: str = ''
            options: Union[:sip:ref:`~PyQt5.QtWidgets.QFontDialog.FontDialogOptions`, :sip:ref:`~PyQt5.QtWidgets.QFontDialog.FontDialogOption`] = QFontDialog.FontDialogOptions()
        :returns:
            :sip:ref:`~PyQt5.QtGui.QFont`
            bool
        :static:
        :description: QtWidgets/QFontDialog-getFont-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QFontDialog.open
        :description: QtWidgets/QFontDialog-open-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFontDialog.open
        :args:
            PYQT_SLOT
        :description: QtWidgets/QFontDialog-open-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QFontDialog.options
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QFontDialog.FontDialogOptions`
        :description: QtWidgets/QFontDialog-options-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFontDialog.selectedFont
        :returns:
            :sip:ref:`~PyQt5.QtGui.QFont`
        :description: QtWidgets/QFontDialog-selectedFont-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFontDialog.setCurrentFont
        :args:
            :sip:ref:`~PyQt5.QtGui.QFont`
        :description: QtWidgets/QFontDialog-setCurrentFont-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFontDialog.setOption
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QFontDialog.FontDialogOption`
            on: bool = True
        :description: QtWidgets/QFontDialog-setOption-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFontDialog.setOptions
        :args:
            Union[:sip:ref:`~PyQt5.QtWidgets.QFontDialog.FontDialogOptions`, :sip:ref:`~PyQt5.QtWidgets.QFontDialog.FontDialogOption`]
        :description: QtWidgets/QFontDialog-setOptions-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFontDialog.setVisible
        :args:
            bool
        :description: QtWidgets/QFontDialog-setVisible-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFontDialog.testOption
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QFontDialog.FontDialogOption`
        :returns:
            bool
        :description: QtWidgets/QFontDialog-testOption-f.rst

    .. sip:signal:: PyQt5.QtWidgets.QFontDialog.currentFontChanged
        :args:
            :sip:ref:`~PyQt5.QtGui.QFont`
        :description: QtWidgets/QFontDialog-currentFontChanged-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QFontDialog.fontSelected
        :args:
            :sip:ref:`~PyQt5.QtGui.QFont`
        :description: QtWidgets/QFontDialog-fontSelected-s.rst
