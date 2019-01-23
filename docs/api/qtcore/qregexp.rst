:orphan:

.. sip:class:: PyQt5.QtCore.QRegExp
    :description: QtCore/QRegExp-c.rst

    .. sip:enum:: PyQt5.QtCore.QRegExp.CaretMode
        :description: QtCore/QRegExp-CaretMode-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QRegExp.CaretMode.CaretAtOffset
            :description: QtCore/QRegExp-CaretMode-CaretAtOffset-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QRegExp.CaretMode.CaretAtZero
            :description: QtCore/QRegExp-CaretMode-CaretAtZero-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QRegExp.CaretMode.CaretWontMatch
            :description: QtCore/QRegExp-CaretMode-CaretWontMatch-v.rst

    .. sip:enum:: PyQt5.QtCore.QRegExp.PatternSyntax
        :description: QtCore/QRegExp-PatternSyntax-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QRegExp.PatternSyntax.FixedString
            :description: QtCore/QRegExp-PatternSyntax-FixedString-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QRegExp.PatternSyntax.RegExp
            :description: QtCore/QRegExp-PatternSyntax-RegExp-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QRegExp.PatternSyntax.RegExp2
            :description: QtCore/QRegExp-PatternSyntax-RegExp2-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QRegExp.PatternSyntax.W3CXmlSchema11
            :description: QtCore/QRegExp-PatternSyntax-W3CXmlSchema11-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QRegExp.PatternSyntax.Wildcard
            :description: QtCore/QRegExp-PatternSyntax-Wildcard-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QRegExp.PatternSyntax.WildcardUnix
            :description: QtCore/QRegExp-PatternSyntax-WildcardUnix-v.rst

    .. sip:method:: PyQt5.QtCore.QRegExp.__init__
        :description: QtCore/QRegExp-__init__-f.rst

    .. sip:method:: PyQt5.QtCore.QRegExp.__init__
        :args:
            :sip:ref:`~PyQt5.QtCore.QRegExp`
        :description: QtCore/QRegExp-__init__-f-1.rst

    .. sip:method:: PyQt5.QtCore.QRegExp.__init__
        :args:
            str
            cs: :sip:ref:`~PyQt5.QtCore.Qt.CaseSensitivity` = :sip:ref:`~PyQt5.QtCore.Qt.CaseSensitivity.CaseSensitive`
            syntax: :sip:ref:`~PyQt5.QtCore.QRegExp.PatternSyntax` = :sip:ref:`~PyQt5.QtCore.QRegExp.PatternSyntax.RegExp`
        :description: QtCore/QRegExp-__init__-f-2.rst

    .. sip:method:: PyQt5.QtCore.QRegExp.cap
        :args:
            nth: int = 0
        :returns:
            str
        :description: QtCore/QRegExp-cap-f.rst

    .. sip:method:: PyQt5.QtCore.QRegExp.captureCount
        :returns:
            int
        :description: QtCore/QRegExp-captureCount-f.rst

    .. sip:method:: PyQt5.QtCore.QRegExp.capturedTexts
        :returns:
            List[str]
        :description: QtCore/QRegExp-capturedTexts-f.rst

    .. sip:method:: PyQt5.QtCore.QRegExp.caseSensitivity
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.CaseSensitivity`
        :description: QtCore/QRegExp-caseSensitivity-f.rst

    .. sip:method:: PyQt5.QtCore.QRegExp.__eq__
        :args:
            :sip:ref:`~PyQt5.QtCore.QRegExp`
        :returns:
            bool
        :description: QtCore/QRegExp-__eq__-f.rst

    .. sip:method:: PyQt5.QtCore.QRegExp.errorString
        :returns:
            str
        :description: QtCore/QRegExp-errorString-f.rst

    .. sip:method:: PyQt5.QtCore.QRegExp.escape
        :args:
            str
        :returns:
            str
        :static:
        :description: QtCore/QRegExp-escape-f.rst

    .. sip:method:: PyQt5.QtCore.QRegExp.exactMatch
        :args:
            str
        :returns:
            bool
        :description: QtCore/QRegExp-exactMatch-f.rst

    .. sip:method:: PyQt5.QtCore.QRegExp.__hash__
        :returns:
            int
        :description: QtCore/QRegExp-__hash__-f.rst

    .. sip:method:: PyQt5.QtCore.QRegExp.indexIn
        :args:
            str
            offset: int = 0
            caretMode: :sip:ref:`~PyQt5.QtCore.QRegExp.CaretMode` = :sip:ref:`~PyQt5.QtCore.QRegExp.CaretMode.CaretAtZero`
        :returns:
            int
        :description: QtCore/QRegExp-indexIn-f.rst

    .. sip:method:: PyQt5.QtCore.QRegExp.isEmpty
        :returns:
            bool
        :description: QtCore/QRegExp-isEmpty-f.rst

    .. sip:method:: PyQt5.QtCore.QRegExp.isMinimal
        :returns:
            bool
        :description: QtCore/QRegExp-isMinimal-f.rst

    .. sip:method:: PyQt5.QtCore.QRegExp.isValid
        :returns:
            bool
        :description: QtCore/QRegExp-isValid-f.rst

    .. sip:method:: PyQt5.QtCore.QRegExp.lastIndexIn
        :args:
            str
            offset: int = -1
            caretMode: :sip:ref:`~PyQt5.QtCore.QRegExp.CaretMode` = :sip:ref:`~PyQt5.QtCore.QRegExp.CaretMode.CaretAtZero`
        :returns:
            int
        :description: QtCore/QRegExp-lastIndexIn-f.rst

    .. sip:method:: PyQt5.QtCore.QRegExp.matchedLength
        :returns:
            int
        :description: QtCore/QRegExp-matchedLength-f.rst

    .. sip:method:: PyQt5.QtCore.QRegExp.__ne__
        :args:
            :sip:ref:`~PyQt5.QtCore.QRegExp`
        :returns:
            bool
        :description: QtCore/QRegExp-__ne__-f.rst

    .. sip:method:: PyQt5.QtCore.QRegExp.pattern
        :returns:
            str
        :description: QtCore/QRegExp-pattern-f.rst

    .. sip:method:: PyQt5.QtCore.QRegExp.patternSyntax
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRegExp.PatternSyntax`
        :description: QtCore/QRegExp-patternSyntax-f.rst

    .. sip:method:: PyQt5.QtCore.QRegExp.pos
        :args:
            nth: int = 0
        :returns:
            int
        :description: QtCore/QRegExp-pos-f.rst

    .. sip:method:: PyQt5.QtCore.QRegExp.__repr__
        :returns:
            str
        :description: QtCore/QRegExp-__repr__-f.rst

    .. sip:method:: PyQt5.QtCore.QRegExp.setCaseSensitivity
        :args:
            :sip:ref:`~PyQt5.QtCore.Qt.CaseSensitivity`
        :description: QtCore/QRegExp-setCaseSensitivity-f.rst

    .. sip:method:: PyQt5.QtCore.QRegExp.setMinimal
        :args:
            bool
        :description: QtCore/QRegExp-setMinimal-f.rst

    .. sip:method:: PyQt5.QtCore.QRegExp.setPattern
        :args:
            str
        :description: QtCore/QRegExp-setPattern-f.rst

    .. sip:method:: PyQt5.QtCore.QRegExp.setPatternSyntax
        :args:
            :sip:ref:`~PyQt5.QtCore.QRegExp.PatternSyntax`
        :description: QtCore/QRegExp-setPatternSyntax-f.rst

    .. sip:method:: PyQt5.QtCore.QRegExp.swap
        :args:
            :sip:ref:`~PyQt5.QtCore.QRegExp`
        :description: QtCore/QRegExp-swap-f.rst
