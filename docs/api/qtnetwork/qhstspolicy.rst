:orphan:

.. sip:class:: PyQt5.QtNetwork.QHstsPolicy
    :description: QtNetwork/QHstsPolicy-c.rst

    .. sip:enum:: PyQt5.QtNetwork.QHstsPolicy.PolicyFlag
        :description: QtNetwork/QHstsPolicy-PolicyFlag-e.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QHstsPolicy.PolicyFlag.IncludeSubDomains
            :description: QtNetwork/QHstsPolicy-PolicyFlag-IncludeSubDomains-v.rst

    .. sip:method:: PyQt5.QtNetwork.QHstsPolicy.__init__
        :description: QtNetwork/QHstsPolicy-__init__-f.rst

    .. sip:method:: PyQt5.QtNetwork.QHstsPolicy.__init__
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QHstsPolicy`
        :description: QtNetwork/QHstsPolicy-__init__-f-1.rst

    .. sip:method:: PyQt5.QtNetwork.QHstsPolicy.__init__
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QDateTime`, datetime.datetime]
            Union[:sip:ref:`~PyQt5.QtNetwork.QHstsPolicy.PolicyFlags`, :sip:ref:`~PyQt5.QtNetwork.QHstsPolicy.PolicyFlag`]
            str
            mode: :sip:ref:`~PyQt5.QtCore.QUrl.ParsingMode` = :sip:ref:`~PyQt5.QtCore.QUrl.ParsingMode.DecodedMode`
        :description: QtNetwork/QHstsPolicy-__init__-f-2.rst

    .. sip:method:: PyQt5.QtNetwork.QHstsPolicy.__eq__
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QHstsPolicy`
        :returns:
            bool
        :description: QtNetwork/QHstsPolicy-__eq__-f.rst

    .. sip:method:: PyQt5.QtNetwork.QHstsPolicy.expiry
        :returns:
            :sip:ref:`~PyQt5.QtCore.QDateTime`
        :description: QtNetwork/QHstsPolicy-expiry-f.rst

    .. sip:method:: PyQt5.QtNetwork.QHstsPolicy.host
        :args:
            options: Union[:sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOptions`, :sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOption`] = QUrl.ComponentFormattingOption.FullyDecoded
        :returns:
            str
        :description: QtNetwork/QHstsPolicy-host-f.rst

    .. sip:method:: PyQt5.QtNetwork.QHstsPolicy.includesSubDomains
        :returns:
            bool
        :description: QtNetwork/QHstsPolicy-includesSubDomains-f.rst

    .. sip:method:: PyQt5.QtNetwork.QHstsPolicy.isExpired
        :returns:
            bool
        :description: QtNetwork/QHstsPolicy-isExpired-f.rst

    .. sip:method:: PyQt5.QtNetwork.QHstsPolicy.__ne__
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QHstsPolicy`
        :returns:
            bool
        :description: QtNetwork/QHstsPolicy-__ne__-f.rst

    .. sip:method:: PyQt5.QtNetwork.QHstsPolicy.setExpiry
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QDateTime`, datetime.datetime]
        :description: QtNetwork/QHstsPolicy-setExpiry-f.rst

    .. sip:method:: PyQt5.QtNetwork.QHstsPolicy.setHost
        :args:
            str
            mode: :sip:ref:`~PyQt5.QtCore.QUrl.ParsingMode` = :sip:ref:`~PyQt5.QtCore.QUrl.ParsingMode.DecodedMode`
        :description: QtNetwork/QHstsPolicy-setHost-f.rst

    .. sip:method:: PyQt5.QtNetwork.QHstsPolicy.setIncludesSubDomains
        :args:
            bool
        :description: QtNetwork/QHstsPolicy-setIncludesSubDomains-f.rst

    .. sip:method:: PyQt5.QtNetwork.QHstsPolicy.swap
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QHstsPolicy`
        :description: QtNetwork/QHstsPolicy-swap-f.rst
