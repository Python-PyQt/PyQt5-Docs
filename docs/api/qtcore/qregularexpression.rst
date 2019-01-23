:orphan:

.. sip:class:: PyQt5.QtCore.QRegularExpression
    :description: QtCore/QRegularExpression-c.rst

    .. sip:enum:: PyQt5.QtCore.QRegularExpression.MatchOption
        :description: QtCore/QRegularExpression-MatchOption-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QRegularExpression.MatchOption.AnchoredMatchOption
            :description: QtCore/QRegularExpression-MatchOption-AnchoredMatchOption-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QRegularExpression.MatchOption.DontCheckSubjectStringMatchOption
            :description: QtCore/QRegularExpression-MatchOption-DontCheckSubjectStringMatchOption-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QRegularExpression.MatchOption.NoMatchOption
            :description: QtCore/QRegularExpression-MatchOption-NoMatchOption-v.rst

    .. sip:enum:: PyQt5.QtCore.QRegularExpression.MatchType
        :description: QtCore/QRegularExpression-MatchType-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QRegularExpression.MatchType.NoMatch
            :description: QtCore/QRegularExpression-MatchType-NoMatch-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QRegularExpression.MatchType.NormalMatch
            :description: QtCore/QRegularExpression-MatchType-NormalMatch-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QRegularExpression.MatchType.PartialPreferCompleteMatch
            :description: QtCore/QRegularExpression-MatchType-PartialPreferCompleteMatch-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QRegularExpression.MatchType.PartialPreferFirstMatch
            :description: QtCore/QRegularExpression-MatchType-PartialPreferFirstMatch-v.rst

    .. sip:enum:: PyQt5.QtCore.QRegularExpression.PatternOption
        :description: QtCore/QRegularExpression-PatternOption-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QRegularExpression.PatternOption.CaseInsensitiveOption
            :description: QtCore/QRegularExpression-PatternOption-CaseInsensitiveOption-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QRegularExpression.PatternOption.DontAutomaticallyOptimizeOption
            :description: QtCore/QRegularExpression-PatternOption-DontAutomaticallyOptimizeOption-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QRegularExpression.PatternOption.DontCaptureOption
            :description: QtCore/QRegularExpression-PatternOption-DontCaptureOption-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QRegularExpression.PatternOption.DotMatchesEverythingOption
            :description: QtCore/QRegularExpression-PatternOption-DotMatchesEverythingOption-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QRegularExpression.PatternOption.ExtendedPatternSyntaxOption
            :description: QtCore/QRegularExpression-PatternOption-ExtendedPatternSyntaxOption-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QRegularExpression.PatternOption.InvertedGreedinessOption
            :description: QtCore/QRegularExpression-PatternOption-InvertedGreedinessOption-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QRegularExpression.PatternOption.MultilineOption
            :description: QtCore/QRegularExpression-PatternOption-MultilineOption-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QRegularExpression.PatternOption.NoPatternOption
            :description: QtCore/QRegularExpression-PatternOption-NoPatternOption-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QRegularExpression.PatternOption.OptimizeOnFirstUsageOption
            :description: QtCore/QRegularExpression-PatternOption-OptimizeOnFirstUsageOption-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QRegularExpression.PatternOption.UseUnicodePropertiesOption
            :description: QtCore/QRegularExpression-PatternOption-UseUnicodePropertiesOption-v.rst

    .. sip:method:: PyQt5.QtCore.QRegularExpression.__init__
        :description: QtCore/QRegularExpression-__init__-f.rst

    .. sip:method:: PyQt5.QtCore.QRegularExpression.__init__
        :args:
            :sip:ref:`~PyQt5.QtCore.QRegularExpression`
        :description: QtCore/QRegularExpression-__init__-f-1.rst

    .. sip:method:: PyQt5.QtCore.QRegularExpression.__init__
        :args:
            str
            options: Union[:sip:ref:`~PyQt5.QtCore.QRegularExpression.PatternOptions`, :sip:ref:`~PyQt5.QtCore.QRegularExpression.PatternOption`] = :sip:ref:`~PyQt5.QtCore.QRegularExpression.PatternOption.NoPatternOption`
        :description: QtCore/QRegularExpression-__init__-f-2.rst

    .. sip:method:: PyQt5.QtCore.QRegularExpression.anchoredPattern
        :args:
            str
        :returns:
            str
        :static:
        :description: QtCore/QRegularExpression-anchoredPattern-f.rst

    .. sip:method:: PyQt5.QtCore.QRegularExpression.captureCount
        :returns:
            int
        :description: QtCore/QRegularExpression-captureCount-f.rst

    .. sip:method:: PyQt5.QtCore.QRegularExpression.__eq__
        :args:
            :sip:ref:`~PyQt5.QtCore.QRegularExpression`
        :returns:
            bool
        :description: QtCore/QRegularExpression-__eq__-f.rst

    .. sip:method:: PyQt5.QtCore.QRegularExpression.errorString
        :returns:
            str
        :description: QtCore/QRegularExpression-errorString-f.rst

    .. sip:method:: PyQt5.QtCore.QRegularExpression.escape
        :args:
            str
        :returns:
            str
        :static:
        :description: QtCore/QRegularExpression-escape-f.rst

    .. sip:method:: PyQt5.QtCore.QRegularExpression.globalMatch
        :args:
            str
            offset: int = 0
            matchType: :sip:ref:`~PyQt5.QtCore.QRegularExpression.MatchType` = :sip:ref:`~PyQt5.QtCore.QRegularExpression.MatchType.NormalMatch`
            matchOptions: Union[:sip:ref:`~PyQt5.QtCore.QRegularExpression.MatchOptions`, :sip:ref:`~PyQt5.QtCore.QRegularExpression.MatchOption`] = :sip:ref:`~PyQt5.QtCore.QRegularExpression.MatchOption.NoMatchOption`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatchIterator`
        :description: QtCore/QRegularExpression-globalMatch-f.rst

    .. sip:method:: PyQt5.QtCore.QRegularExpression.__hash__
        :returns:
            int
        :description: QtCore/QRegularExpression-__hash__-f.rst

    .. sip:method:: PyQt5.QtCore.QRegularExpression.isValid
        :returns:
            bool
        :description: QtCore/QRegularExpression-isValid-f.rst

    .. sip:method:: PyQt5.QtCore.QRegularExpression.match
        :args:
            str
            offset: int = 0
            matchType: :sip:ref:`~PyQt5.QtCore.QRegularExpression.MatchType` = :sip:ref:`~PyQt5.QtCore.QRegularExpression.MatchType.NormalMatch`
            matchOptions: Union[:sip:ref:`~PyQt5.QtCore.QRegularExpression.MatchOptions`, :sip:ref:`~PyQt5.QtCore.QRegularExpression.MatchOption`] = :sip:ref:`~PyQt5.QtCore.QRegularExpression.MatchOption.NoMatchOption`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatch`
        :description: QtCore/QRegularExpression-match-f.rst

    .. sip:method:: PyQt5.QtCore.QRegularExpression.namedCaptureGroups
        :returns:
            List[str]
        :description: QtCore/QRegularExpression-namedCaptureGroups-f.rst

    .. sip:method:: PyQt5.QtCore.QRegularExpression.__ne__
        :args:
            :sip:ref:`~PyQt5.QtCore.QRegularExpression`
        :returns:
            bool
        :description: QtCore/QRegularExpression-__ne__-f.rst

    .. sip:method:: PyQt5.QtCore.QRegularExpression.optimize
        :description: QtCore/QRegularExpression-optimize-f.rst

    .. sip:method:: PyQt5.QtCore.QRegularExpression.pattern
        :returns:
            str
        :description: QtCore/QRegularExpression-pattern-f.rst

    .. sip:method:: PyQt5.QtCore.QRegularExpression.patternErrorOffset
        :returns:
            int
        :description: QtCore/QRegularExpression-patternErrorOffset-f.rst

    .. sip:method:: PyQt5.QtCore.QRegularExpression.patternOptions
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRegularExpression.PatternOptions`
        :description: QtCore/QRegularExpression-patternOptions-f.rst

    .. sip:method:: PyQt5.QtCore.QRegularExpression.__repr__
        :returns:
            str
        :description: QtCore/QRegularExpression-__repr__-f.rst

    .. sip:method:: PyQt5.QtCore.QRegularExpression.setPattern
        :args:
            str
        :description: QtCore/QRegularExpression-setPattern-f.rst

    .. sip:method:: PyQt5.QtCore.QRegularExpression.setPatternOptions
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QRegularExpression.PatternOptions`, :sip:ref:`~PyQt5.QtCore.QRegularExpression.PatternOption`]
        :description: QtCore/QRegularExpression-setPatternOptions-f.rst

    .. sip:method:: PyQt5.QtCore.QRegularExpression.swap
        :args:
            :sip:ref:`~PyQt5.QtCore.QRegularExpression`
        :description: QtCore/QRegularExpression-swap-f.rst

    .. sip:method:: PyQt5.QtCore.QRegularExpression.wildcardToRegularExpression
        :args:
            str
        :returns:
            str
        :static:
        :description: QtCore/QRegularExpression-wildcardToRegularExpression-f.rst
