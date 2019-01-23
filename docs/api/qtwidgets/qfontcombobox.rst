:orphan:

.. sip:class:: PyQt5.QtWidgets.QFontComboBox
    :inherits: :sip:ref:`~PyQt5.QtWidgets.QComboBox`
    :description: QtWidgets/QFontComboBox-c.rst

    .. sip:enum:: PyQt5.QtWidgets.QFontComboBox.FontFilter
        :description: QtWidgets/QFontComboBox-FontFilter-e.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFontComboBox.FontFilter.AllFonts
            :description: QtWidgets/QFontComboBox-FontFilter-AllFonts-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFontComboBox.FontFilter.MonospacedFonts
            :description: QtWidgets/QFontComboBox-FontFilter-MonospacedFonts-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFontComboBox.FontFilter.NonScalableFonts
            :description: QtWidgets/QFontComboBox-FontFilter-NonScalableFonts-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFontComboBox.FontFilter.ProportionalFonts
            :description: QtWidgets/QFontComboBox-FontFilter-ProportionalFonts-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFontComboBox.FontFilter.ScalableFonts
            :description: QtWidgets/QFontComboBox-FontFilter-ScalableFonts-v.rst

    .. sip:method:: PyQt5.QtWidgets.QFontComboBox.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
        :description: QtWidgets/QFontComboBox-__init__-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFontComboBox.currentFont
        :returns:
            :sip:ref:`~PyQt5.QtGui.QFont`
        :description: QtWidgets/QFontComboBox-currentFont-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFontComboBox.event
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtWidgets/QFontComboBox-event-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFontComboBox.fontFilters
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QFontComboBox.FontFilters`
        :description: QtWidgets/QFontComboBox-fontFilters-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFontComboBox.setCurrentFont
        :args:
            :sip:ref:`~PyQt5.QtGui.QFont`
        :description: QtWidgets/QFontComboBox-setCurrentFont-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFontComboBox.setFontFilters
        :args:
            Union[:sip:ref:`~PyQt5.QtWidgets.QFontComboBox.FontFilters`, :sip:ref:`~PyQt5.QtWidgets.QFontComboBox.FontFilter`]
        :description: QtWidgets/QFontComboBox-setFontFilters-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFontComboBox.setWritingSystem
        :args:
            :sip:ref:`~PyQt5.QtGui.QFontDatabase.WritingSystem`
        :description: QtWidgets/QFontComboBox-setWritingSystem-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFontComboBox.sizeHint
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtWidgets/QFontComboBox-sizeHint-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFontComboBox.writingSystem
        :returns:
            :sip:ref:`~PyQt5.QtGui.QFontDatabase.WritingSystem`
        :description: QtWidgets/QFontComboBox-writingSystem-f.rst

    .. sip:signal:: PyQt5.QtWidgets.QFontComboBox.currentFontChanged
        :args:
            :sip:ref:`~PyQt5.QtGui.QFont`
        :description: QtWidgets/QFontComboBox-currentFontChanged-s.rst
