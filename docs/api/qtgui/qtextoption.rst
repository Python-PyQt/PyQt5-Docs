:orphan:

.. sip:class:: PyQt5.QtGui.QTextOption
    :description: QtGui/QTextOption-c.rst

    .. sip:enum:: PyQt5.QtGui.QTextOption.Flag
        :description: QtGui/QTextOption-Flag-e.rst

        .. sip:enum-member:: PyQt5.QtGui.QTextOption.Flag.AddSpaceForLineAndParagraphSeparators
            :description: QtGui/QTextOption-Flag-AddSpaceForLineAndParagraphSeparators-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QTextOption.Flag.IncludeTrailingSpaces
            :description: QtGui/QTextOption-Flag-IncludeTrailingSpaces-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QTextOption.Flag.ShowDocumentTerminator
            :description: QtGui/QTextOption-Flag-ShowDocumentTerminator-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QTextOption.Flag.ShowLineAndParagraphSeparators
            :description: QtGui/QTextOption-Flag-ShowLineAndParagraphSeparators-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QTextOption.Flag.ShowTabsAndSpaces
            :description: QtGui/QTextOption-Flag-ShowTabsAndSpaces-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QTextOption.Flag.SuppressColors
            :description: QtGui/QTextOption-Flag-SuppressColors-v.rst

    .. sip:enum:: PyQt5.QtGui.QTextOption.TabType
        :description: QtGui/QTextOption-TabType-e.rst

        .. sip:enum-member:: PyQt5.QtGui.QTextOption.TabType.CenterTab
            :description: QtGui/QTextOption-TabType-CenterTab-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QTextOption.TabType.DelimiterTab
            :description: QtGui/QTextOption-TabType-DelimiterTab-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QTextOption.TabType.LeftTab
            :description: QtGui/QTextOption-TabType-LeftTab-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QTextOption.TabType.RightTab
            :description: QtGui/QTextOption-TabType-RightTab-v.rst

    .. sip:enum:: PyQt5.QtGui.QTextOption.WrapMode
        :description: QtGui/QTextOption-WrapMode-e.rst

        .. sip:enum-member:: PyQt5.QtGui.QTextOption.WrapMode.ManualWrap
            :description: QtGui/QTextOption-WrapMode-ManualWrap-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QTextOption.WrapMode.NoWrap
            :description: QtGui/QTextOption-WrapMode-NoWrap-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QTextOption.WrapMode.WordWrap
            :description: QtGui/QTextOption-WrapMode-WordWrap-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QTextOption.WrapMode.WrapAnywhere
            :description: QtGui/QTextOption-WrapMode-WrapAnywhere-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QTextOption.WrapMode.WrapAtWordBoundaryOrAnywhere
            :description: QtGui/QTextOption-WrapMode-WrapAtWordBoundaryOrAnywhere-v.rst

    .. sip:method:: PyQt5.QtGui.QTextOption.__init__
        :description: QtGui/QTextOption-__init__-f.rst

    .. sip:method:: PyQt5.QtGui.QTextOption.__init__
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.Qt.Alignment`, :sip:ref:`~PyQt5.QtCore.Qt.AlignmentFlag`]
        :description: QtGui/QTextOption-__init__-f-1.rst

    .. sip:method:: PyQt5.QtGui.QTextOption.__init__
        :args:
            :sip:ref:`~PyQt5.QtGui.QTextOption`
        :description: QtGui/QTextOption-__init__-f-2.rst

    .. sip:method:: PyQt5.QtGui.QTextOption.alignment
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.Alignment`
        :description: QtGui/QTextOption-alignment-f.rst

    .. sip:method:: PyQt5.QtGui.QTextOption.flags
        :returns:
            :sip:ref:`~PyQt5.QtGui.QTextOption.Flags`
        :description: QtGui/QTextOption-flags-f.rst

    .. sip:method:: PyQt5.QtGui.QTextOption.setAlignment
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.Qt.Alignment`, :sip:ref:`~PyQt5.QtCore.Qt.AlignmentFlag`]
        :description: QtGui/QTextOption-setAlignment-f.rst

    .. sip:method:: PyQt5.QtGui.QTextOption.setFlags
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QTextOption.Flags`, :sip:ref:`~PyQt5.QtGui.QTextOption.Flag`]
        :description: QtGui/QTextOption-setFlags-f.rst

    .. sip:method:: PyQt5.QtGui.QTextOption.setTabArray
        :args:
            Iterable[float]
        :description: QtGui/QTextOption-setTabArray-f.rst

    .. sip:method:: PyQt5.QtGui.QTextOption.setTabs
        :args:
            Iterable[:sip:ref:`~PyQt5.QtGui.QTextOption.Tab`]
        :description: QtGui/QTextOption-setTabs-f.rst

    .. sip:method:: PyQt5.QtGui.QTextOption.setTabStop
        :args:
            float
        :description: QtGui/QTextOption-setTabStop-f.rst

    .. sip:method:: PyQt5.QtGui.QTextOption.setTabStopDistance
        :args:
            float
        :description: QtGui/QTextOption-setTabStopDistance-f.rst

    .. sip:method:: PyQt5.QtGui.QTextOption.setTextDirection
        :args:
            :sip:ref:`~PyQt5.QtCore.Qt.LayoutDirection`
        :description: QtGui/QTextOption-setTextDirection-f.rst

    .. sip:method:: PyQt5.QtGui.QTextOption.setUseDesignMetrics
        :args:
            bool
        :description: QtGui/QTextOption-setUseDesignMetrics-f.rst

    .. sip:method:: PyQt5.QtGui.QTextOption.setWrapMode
        :args:
            :sip:ref:`~PyQt5.QtGui.QTextOption.WrapMode`
        :description: QtGui/QTextOption-setWrapMode-f.rst

    .. sip:method:: PyQt5.QtGui.QTextOption.tabArray
        :returns:
            List[float]
        :description: QtGui/QTextOption-tabArray-f.rst

    .. sip:method:: PyQt5.QtGui.QTextOption.tabs
        :returns:
            List[:sip:ref:`~PyQt5.QtGui.QTextOption.Tab`]
        :description: QtGui/QTextOption-tabs-f.rst

    .. sip:method:: PyQt5.QtGui.QTextOption.tabStop
        :returns:
            float
        :description: QtGui/QTextOption-tabStop-f.rst

    .. sip:method:: PyQt5.QtGui.QTextOption.tabStopDistance
        :returns:
            float
        :description: QtGui/QTextOption-tabStopDistance-f.rst

    .. sip:method:: PyQt5.QtGui.QTextOption.textDirection
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.LayoutDirection`
        :description: QtGui/QTextOption-textDirection-f.rst

    .. sip:method:: PyQt5.QtGui.QTextOption.useDesignMetrics
        :returns:
            bool
        :description: QtGui/QTextOption-useDesignMetrics-f.rst

    .. sip:method:: PyQt5.QtGui.QTextOption.wrapMode
        :returns:
            :sip:ref:`~PyQt5.QtGui.QTextOption.WrapMode`
        :description: QtGui/QTextOption-wrapMode-f.rst
