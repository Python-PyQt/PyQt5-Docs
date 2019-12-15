:orphan:

.. sip:class:: PyQt5.QtGui.QTextBlockFormat
    :inherits: :sip:ref:`~PyQt5.QtGui.QTextFormat`
    :description: QtGui/QTextBlockFormat-c.rst

    .. sip:enum:: PyQt5.QtGui.QTextBlockFormat.LineHeightTypes
        :description: QtGui/QTextBlockFormat-LineHeightTypes-e.rst

        .. sip:enum-member:: PyQt5.QtGui.QTextBlockFormat.LineHeightTypes.FixedHeight
            :description: QtGui/QTextBlockFormat-LineHeightTypes-FixedHeight-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QTextBlockFormat.LineHeightTypes.LineDistanceHeight
            :description: QtGui/QTextBlockFormat-LineHeightTypes-LineDistanceHeight-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QTextBlockFormat.LineHeightTypes.MinimumHeight
            :description: QtGui/QTextBlockFormat-LineHeightTypes-MinimumHeight-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QTextBlockFormat.LineHeightTypes.ProportionalHeight
            :description: QtGui/QTextBlockFormat-LineHeightTypes-ProportionalHeight-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QTextBlockFormat.LineHeightTypes.SingleHeight
            :description: QtGui/QTextBlockFormat-LineHeightTypes-SingleHeight-v.rst

    .. sip:enum:: PyQt5.QtGui.QTextBlockFormat.MarkerType
        :description: QtGui/QTextBlockFormat-MarkerType-e.rst

        .. sip:enum-member:: PyQt5.QtGui.QTextBlockFormat.MarkerType.Checked
            :description: QtGui/QTextBlockFormat-MarkerType-Checked-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QTextBlockFormat.MarkerType.NoMarker
            :description: QtGui/QTextBlockFormat-MarkerType-NoMarker-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QTextBlockFormat.MarkerType.Unchecked
            :description: QtGui/QTextBlockFormat-MarkerType-Unchecked-v.rst

    .. sip:method:: PyQt5.QtGui.QTextBlockFormat.__init__
        :description: QtGui/QTextBlockFormat-__init__-f.rst

    .. sip:method:: PyQt5.QtGui.QTextBlockFormat.__init__
        :args:
            :sip:ref:`~PyQt5.QtGui.QTextBlockFormat`
        :description: QtGui/QTextBlockFormat-__init__-f-1.rst

    .. sip:method:: PyQt5.QtGui.QTextBlockFormat.alignment
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.Alignment`
        :description: QtGui/QTextBlockFormat-alignment-f.rst

    .. sip:method:: PyQt5.QtGui.QTextBlockFormat.bottomMargin
        :returns:
            float
        :description: QtGui/QTextBlockFormat-bottomMargin-f.rst

    .. sip:method:: PyQt5.QtGui.QTextBlockFormat.headingLevel
        :returns:
            int
        :description: QtGui/QTextBlockFormat-headingLevel-f.rst

    .. sip:method:: PyQt5.QtGui.QTextBlockFormat.indent
        :returns:
            int
        :description: QtGui/QTextBlockFormat-indent-f.rst

    .. sip:method:: PyQt5.QtGui.QTextBlockFormat.isValid
        :returns:
            bool
        :description: QtGui/QTextBlockFormat-isValid-f.rst

    .. sip:method:: PyQt5.QtGui.QTextBlockFormat.leftMargin
        :returns:
            float
        :description: QtGui/QTextBlockFormat-leftMargin-f.rst

    .. sip:method:: PyQt5.QtGui.QTextBlockFormat.lineHeight
        :returns:
            float
        :description: QtGui/QTextBlockFormat-lineHeight-f.rst

    .. sip:method:: PyQt5.QtGui.QTextBlockFormat.lineHeight
        :args:
            float
            scaling: float = 1
        :returns:
            float
        :description: QtGui/QTextBlockFormat-lineHeight-f-1.rst

    .. sip:method:: PyQt5.QtGui.QTextBlockFormat.lineHeightType
        :returns:
            int
        :description: QtGui/QTextBlockFormat-lineHeightType-f.rst

    .. sip:method:: PyQt5.QtGui.QTextBlockFormat.marker
        :returns:
            :sip:ref:`~PyQt5.QtGui.QTextBlockFormat.MarkerType`
        :description: QtGui/QTextBlockFormat-marker-f.rst

    .. sip:method:: PyQt5.QtGui.QTextBlockFormat.nonBreakableLines
        :returns:
            bool
        :description: QtGui/QTextBlockFormat-nonBreakableLines-f.rst

    .. sip:method:: PyQt5.QtGui.QTextBlockFormat.pageBreakPolicy
        :returns:
            :sip:ref:`~PyQt5.QtGui.QTextFormat.PageBreakFlags`
        :description: QtGui/QTextBlockFormat-pageBreakPolicy-f.rst

    .. sip:method:: PyQt5.QtGui.QTextBlockFormat.rightMargin
        :returns:
            float
        :description: QtGui/QTextBlockFormat-rightMargin-f.rst

    .. sip:method:: PyQt5.QtGui.QTextBlockFormat.setAlignment
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.Qt.Alignment`, :sip:ref:`~PyQt5.QtCore.Qt.AlignmentFlag`]
        :description: QtGui/QTextBlockFormat-setAlignment-f.rst

    .. sip:method:: PyQt5.QtGui.QTextBlockFormat.setBottomMargin
        :args:
            float
        :description: QtGui/QTextBlockFormat-setBottomMargin-f.rst

    .. sip:method:: PyQt5.QtGui.QTextBlockFormat.setHeadingLevel
        :args:
            int
        :description: QtGui/QTextBlockFormat-setHeadingLevel-f.rst

    .. sip:method:: PyQt5.QtGui.QTextBlockFormat.setIndent
        :args:
            int
        :description: QtGui/QTextBlockFormat-setIndent-f.rst

    .. sip:method:: PyQt5.QtGui.QTextBlockFormat.setLeftMargin
        :args:
            float
        :description: QtGui/QTextBlockFormat-setLeftMargin-f.rst

    .. sip:method:: PyQt5.QtGui.QTextBlockFormat.setLineHeight
        :args:
            float
            int
        :description: QtGui/QTextBlockFormat-setLineHeight-f.rst

    .. sip:method:: PyQt5.QtGui.QTextBlockFormat.setMarker
        :args:
            :sip:ref:`~PyQt5.QtGui.QTextBlockFormat.MarkerType`
        :description: QtGui/QTextBlockFormat-setMarker-f.rst

    .. sip:method:: PyQt5.QtGui.QTextBlockFormat.setNonBreakableLines
        :args:
            bool
        :description: QtGui/QTextBlockFormat-setNonBreakableLines-f.rst

    .. sip:method:: PyQt5.QtGui.QTextBlockFormat.setPageBreakPolicy
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QTextFormat.PageBreakFlags`, :sip:ref:`~PyQt5.QtGui.QTextFormat.PageBreakFlag`]
        :description: QtGui/QTextBlockFormat-setPageBreakPolicy-f.rst

    .. sip:method:: PyQt5.QtGui.QTextBlockFormat.setRightMargin
        :args:
            float
        :description: QtGui/QTextBlockFormat-setRightMargin-f.rst

    .. sip:method:: PyQt5.QtGui.QTextBlockFormat.setTabPositions
        :args:
            Iterable[:sip:ref:`~PyQt5.QtGui.QTextOption.Tab`]
        :description: QtGui/QTextBlockFormat-setTabPositions-f.rst

    .. sip:method:: PyQt5.QtGui.QTextBlockFormat.setTextIndent
        :args:
            float
        :description: QtGui/QTextBlockFormat-setTextIndent-f.rst

    .. sip:method:: PyQt5.QtGui.QTextBlockFormat.setTopMargin
        :args:
            float
        :description: QtGui/QTextBlockFormat-setTopMargin-f.rst

    .. sip:method:: PyQt5.QtGui.QTextBlockFormat.tabPositions
        :returns:
            List[:sip:ref:`~PyQt5.QtGui.QTextOption.Tab`]
        :description: QtGui/QTextBlockFormat-tabPositions-f.rst

    .. sip:method:: PyQt5.QtGui.QTextBlockFormat.textIndent
        :returns:
            float
        :description: QtGui/QTextBlockFormat-textIndent-f.rst

    .. sip:method:: PyQt5.QtGui.QTextBlockFormat.topMargin
        :returns:
            float
        :description: QtGui/QTextBlockFormat-topMargin-f.rst
