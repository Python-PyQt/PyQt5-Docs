:orphan:

.. sip:class:: PyQt5.QtGui.QInputMethodEvent
    :inherits: :sip:ref:`~PyQt5.QtCore.QEvent`
    :description: QtGui/QInputMethodEvent-c.rst

    .. sip:enum:: PyQt5.QtGui.QInputMethodEvent.AttributeType
        :description: QtGui/QInputMethodEvent-AttributeType-e.rst

        .. sip:enum-member:: PyQt5.QtGui.QInputMethodEvent.AttributeType.Cursor
            :description: QtGui/QInputMethodEvent-AttributeType-Cursor-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QInputMethodEvent.AttributeType.Language
            :description: QtGui/QInputMethodEvent-AttributeType-Language-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QInputMethodEvent.AttributeType.Ruby
            :description: QtGui/QInputMethodEvent-AttributeType-Ruby-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QInputMethodEvent.AttributeType.Selection
            :description: QtGui/QInputMethodEvent-AttributeType-Selection-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QInputMethodEvent.AttributeType.TextFormat
            :description: QtGui/QInputMethodEvent-AttributeType-TextFormat-v.rst

    .. sip:method:: PyQt5.QtGui.QInputMethodEvent.__init__
        :description: QtGui/QInputMethodEvent-__init__-f.rst

    .. sip:method:: PyQt5.QtGui.QInputMethodEvent.__init__
        :args:
            :sip:ref:`~PyQt5.QtGui.QInputMethodEvent`
        :description: QtGui/QInputMethodEvent-__init__-f-1.rst

    .. sip:method:: PyQt5.QtGui.QInputMethodEvent.__init__
        :args:
            str
            Iterable[:sip:ref:`~PyQt5.QtGui.QInputMethodEvent.Attribute`]
        :description: QtGui/QInputMethodEvent-__init__-f-2.rst

    .. sip:method:: PyQt5.QtGui.QInputMethodEvent.attributes
        :returns:
            List[:sip:ref:`~PyQt5.QtGui.QInputMethodEvent.Attribute`]
        :description: QtGui/QInputMethodEvent-attributes-f.rst

    .. sip:method:: PyQt5.QtGui.QInputMethodEvent.commitString
        :returns:
            str
        :description: QtGui/QInputMethodEvent-commitString-f.rst

    .. sip:method:: PyQt5.QtGui.QInputMethodEvent.preeditString
        :returns:
            str
        :description: QtGui/QInputMethodEvent-preeditString-f.rst

    .. sip:method:: PyQt5.QtGui.QInputMethodEvent.replacementLength
        :returns:
            int
        :description: QtGui/QInputMethodEvent-replacementLength-f.rst

    .. sip:method:: PyQt5.QtGui.QInputMethodEvent.replacementStart
        :returns:
            int
        :description: QtGui/QInputMethodEvent-replacementStart-f.rst

    .. sip:method:: PyQt5.QtGui.QInputMethodEvent.setCommitString
        :args:
            str
            from: int = 0
            length: int = 0
        :description: QtGui/QInputMethodEvent-setCommitString-f.rst
