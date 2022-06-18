:orphan:

.. sip:class:: PyQt5.QtCore.QUrl
    :description: QtCore/QUrl-c.rst

    .. sip:enum:: PyQt5.QtCore.QUrl.ComponentFormattingOption
        :description: QtCore/QUrl-ComponentFormattingOption-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QUrl.ComponentFormattingOption.DecodeReserved
            :description: QtCore/QUrl-ComponentFormattingOption-DecodeReserved-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QUrl.ComponentFormattingOption.EncodeDelimiters
            :description: QtCore/QUrl-ComponentFormattingOption-EncodeDelimiters-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QUrl.ComponentFormattingOption.EncodeReserved
            :description: QtCore/QUrl-ComponentFormattingOption-EncodeReserved-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QUrl.ComponentFormattingOption.EncodeSpaces
            :description: QtCore/QUrl-ComponentFormattingOption-EncodeSpaces-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QUrl.ComponentFormattingOption.EncodeUnicode
            :description: QtCore/QUrl-ComponentFormattingOption-EncodeUnicode-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QUrl.ComponentFormattingOption.FullyDecoded
            :description: QtCore/QUrl-ComponentFormattingOption-FullyDecoded-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QUrl.ComponentFormattingOption.FullyEncoded
            :description: QtCore/QUrl-ComponentFormattingOption-FullyEncoded-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QUrl.ComponentFormattingOption.PrettyDecoded
            :description: QtCore/QUrl-ComponentFormattingOption-PrettyDecoded-v.rst

    .. sip:enum:: PyQt5.QtCore.QUrl.ParsingMode
        :description: QtCore/QUrl-ParsingMode-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QUrl.ParsingMode.DecodedMode
            :description: QtCore/QUrl-ParsingMode-DecodedMode-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QUrl.ParsingMode.StrictMode
            :description: QtCore/QUrl-ParsingMode-StrictMode-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QUrl.ParsingMode.TolerantMode
            :description: QtCore/QUrl-ParsingMode-TolerantMode-v.rst

    .. sip:enum:: PyQt5.QtCore.QUrl.UrlFormattingOption
        :description: QtCore/QUrl-UrlFormattingOption-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QUrl.UrlFormattingOption.None_
            :description: QtCore/QUrl-UrlFormattingOption-None_-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QUrl.UrlFormattingOption.NormalizePathSegments
            :description: QtCore/QUrl-UrlFormattingOption-NormalizePathSegments-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QUrl.UrlFormattingOption.PreferLocalFile
            :description: QtCore/QUrl-UrlFormattingOption-PreferLocalFile-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QUrl.UrlFormattingOption.RemoveAuthority
            :description: QtCore/QUrl-UrlFormattingOption-RemoveAuthority-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QUrl.UrlFormattingOption.RemoveFilename
            :description: QtCore/QUrl-UrlFormattingOption-RemoveFilename-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QUrl.UrlFormattingOption.RemoveFragment
            :description: QtCore/QUrl-UrlFormattingOption-RemoveFragment-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QUrl.UrlFormattingOption.RemovePassword
            :description: QtCore/QUrl-UrlFormattingOption-RemovePassword-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QUrl.UrlFormattingOption.RemovePath
            :description: QtCore/QUrl-UrlFormattingOption-RemovePath-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QUrl.UrlFormattingOption.RemovePort
            :description: QtCore/QUrl-UrlFormattingOption-RemovePort-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QUrl.UrlFormattingOption.RemoveQuery
            :description: QtCore/QUrl-UrlFormattingOption-RemoveQuery-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QUrl.UrlFormattingOption.RemoveScheme
            :description: QtCore/QUrl-UrlFormattingOption-RemoveScheme-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QUrl.UrlFormattingOption.RemoveUserInfo
            :description: QtCore/QUrl-UrlFormattingOption-RemoveUserInfo-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QUrl.UrlFormattingOption.StripTrailingSlash
            :description: QtCore/QUrl-UrlFormattingOption-StripTrailingSlash-v.rst

    .. sip:enum:: PyQt5.QtCore.QUrl.UserInputResolutionOption
        :description: QtCore/QUrl-UserInputResolutionOption-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QUrl.UserInputResolutionOption.AssumeLocalFile
            :description: QtCore/QUrl-UserInputResolutionOption-AssumeLocalFile-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QUrl.UserInputResolutionOption.DefaultResolution
            :description: QtCore/QUrl-UserInputResolutionOption-DefaultResolution-v.rst

    .. sip:method:: PyQt5.QtCore.QUrl.__init__
        :description: QtCore/QUrl-__init__-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.__init__
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtCore/QUrl-__init__-f-1.rst

    .. sip:method:: PyQt5.QtCore.QUrl.__init__
        :args:
            str
            mode: :sip:ref:`~PyQt5.QtCore.QUrl.ParsingMode` = :sip:ref:`~PyQt5.QtCore.QUrl.ParsingMode.TolerantMode`
        :description: QtCore/QUrl-__init__-f-2.rst

    .. sip:method:: PyQt5.QtCore.QUrl.adjusted
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QUrl.FormattingOptions`, :sip:ref:`~PyQt5.QtCore.QUrl.UrlFormattingOption`, :sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOption`]
        :returns:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtCore/QUrl-adjusted-f-1.rst

    .. sip:method:: PyQt5.QtCore.QUrl.authority
        :args:
            options: Union[:sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOptions`, :sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOption`] = :sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOption.PrettyDecoded`
        :returns:
            str
        :description: QtCore/QUrl-authority-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.clear
        :description: QtCore/QUrl-clear-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.detach
        :description: QtCore/QUrl-detach-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.__eq__
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :returns:
            bool
        :description: QtCore/QUrl-__eq__-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.errorString
        :returns:
            str
        :description: QtCore/QUrl-errorString-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.fileName
        :args:
            options: Union[:sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOptions`, :sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOption`] = :sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOption.FullyDecoded`
        :returns:
            str
        :description: QtCore/QUrl-fileName-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.fragment
        :args:
            options: Union[:sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOptions`, :sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOption`] = :sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOption.PrettyDecoded`
        :returns:
            str
        :description: QtCore/QUrl-fragment-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.fromAce
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :returns:
            str
        :static:
        :description: QtCore/QUrl-fromAce-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.fromEncoded
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
            mode: :sip:ref:`~PyQt5.QtCore.QUrl.ParsingMode` = :sip:ref:`~PyQt5.QtCore.QUrl.ParsingMode.TolerantMode`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :static:
        :description: QtCore/QUrl-fromEncoded-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.fromLocalFile
        :args:
            str
        :returns:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :static:
        :description: QtCore/QUrl-fromLocalFile-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.fromPercentEncoding
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :returns:
            str
        :static:
        :description: QtCore/QUrl-fromPercentEncoding-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.fromStringList
        :args:
            Iterable[str]
            mode: :sip:ref:`~PyQt5.QtCore.QUrl.ParsingMode` = :sip:ref:`~PyQt5.QtCore.QUrl.ParsingMode.TolerantMode`
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QUrl`]
        :static:
        :description: QtCore/QUrl-fromStringList-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.fromUserInput
        :args:
            str
        :returns:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :static:
        :description: QtCore/QUrl-fromUserInput-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.fromUserInput
        :args:
            str
            str
            options: Union[:sip:ref:`~PyQt5.QtCore.QUrl.UserInputResolutionOptions`, :sip:ref:`~PyQt5.QtCore.QUrl.UserInputResolutionOption`] = :sip:ref:`~PyQt5.QtCore.QUrl.UserInputResolutionOption.DefaultResolution`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :static:
        :description: QtCore/QUrl-fromUserInput-f-1.rst

    .. sip:method:: PyQt5.QtCore.QUrl.__ge__
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :returns:
            bool
        :description: QtCore/QUrl-__ge__-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.hasFragment
        :returns:
            bool
        :description: QtCore/QUrl-hasFragment-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.__hash__
        :returns:
            int
        :description: QtCore/QUrl-__hash__-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.hasQuery
        :returns:
            bool
        :description: QtCore/QUrl-hasQuery-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.host
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOptions`, :sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOption`]
        :returns:
            str
        :description: QtCore/QUrl-host-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.idnWhitelist
        :returns:
            List[str]
        :static:
        :description: QtCore/QUrl-idnWhitelist-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.isDetached
        :returns:
            bool
        :description: QtCore/QUrl-isDetached-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.isEmpty
        :returns:
            bool
        :description: QtCore/QUrl-isEmpty-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.isLocalFile
        :returns:
            bool
        :description: QtCore/QUrl-isLocalFile-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.isParentOf
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :returns:
            bool
        :description: QtCore/QUrl-isParentOf-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.isRelative
        :returns:
            bool
        :description: QtCore/QUrl-isRelative-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.isValid
        :returns:
            bool
        :description: QtCore/QUrl-isValid-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.__lt__
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :returns:
            bool
        :description: QtCore/QUrl-__lt__-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.matches
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
            Union[:sip:ref:`~PyQt5.QtCore.QUrl.FormattingOptions`, :sip:ref:`~PyQt5.QtCore.QUrl.UrlFormattingOption`, :sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOption`]
        :returns:
            bool
        :description: QtCore/QUrl-matches-f-1.rst

    .. sip:method:: PyQt5.QtCore.QUrl.__ne__
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :returns:
            bool
        :description: QtCore/QUrl-__ne__-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.password
        :args:
            options: Union[:sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOptions`, :sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOption`] = :sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOption.FullyDecoded`
        :returns:
            str
        :description: QtCore/QUrl-password-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.path
        :args:
            options: Union[:sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOptions`, :sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOption`] = :sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOption.FullyDecoded`
        :returns:
            str
        :description: QtCore/QUrl-path-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.port
        :args:
            defaultPort: int = -1
        :returns:
            int
        :description: QtCore/QUrl-port-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.query
        :args:
            options: Union[:sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOptions`, :sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOption`] = :sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOption.PrettyDecoded`
        :returns:
            str
        :description: QtCore/QUrl-query-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.__repr__
        :returns:
            str
        :description: QtCore/QUrl-__repr__-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.resolved
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtCore/QUrl-resolved-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.scheme
        :returns:
            str
        :description: QtCore/QUrl-scheme-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.setAuthority
        :args:
            str
            mode: :sip:ref:`~PyQt5.QtCore.QUrl.ParsingMode` = :sip:ref:`~PyQt5.QtCore.QUrl.ParsingMode.TolerantMode`
        :description: QtCore/QUrl-setAuthority-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.setFragment
        :args:
            str
            mode: :sip:ref:`~PyQt5.QtCore.QUrl.ParsingMode` = :sip:ref:`~PyQt5.QtCore.QUrl.ParsingMode.TolerantMode`
        :description: QtCore/QUrl-setFragment-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.setHost
        :args:
            str
            mode: :sip:ref:`~PyQt5.QtCore.QUrl.ParsingMode` = :sip:ref:`~PyQt5.QtCore.QUrl.ParsingMode.DecodedMode`
        :description: QtCore/QUrl-setHost-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.setIdnWhitelist
        :args:
            Iterable[str]
        :static:
        :description: QtCore/QUrl-setIdnWhitelist-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.setPassword
        :args:
            str
            mode: :sip:ref:`~PyQt5.QtCore.QUrl.ParsingMode` = :sip:ref:`~PyQt5.QtCore.QUrl.ParsingMode.DecodedMode`
        :description: QtCore/QUrl-setPassword-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.setPath
        :args:
            str
            mode: :sip:ref:`~PyQt5.QtCore.QUrl.ParsingMode` = :sip:ref:`~PyQt5.QtCore.QUrl.ParsingMode.DecodedMode`
        :description: QtCore/QUrl-setPath-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.setPort
        :args:
            int
        :description: QtCore/QUrl-setPort-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.setQuery
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrlQuery`
        :description: QtCore/QUrl-setQuery-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.setQuery
        :args:
            str
            mode: :sip:ref:`~PyQt5.QtCore.QUrl.ParsingMode` = :sip:ref:`~PyQt5.QtCore.QUrl.ParsingMode.TolerantMode`
        :description: QtCore/QUrl-setQuery-f-1.rst

    .. sip:method:: PyQt5.QtCore.QUrl.setScheme
        :args:
            str
        :description: QtCore/QUrl-setScheme-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.setUrl
        :args:
            str
            mode: :sip:ref:`~PyQt5.QtCore.QUrl.ParsingMode` = :sip:ref:`~PyQt5.QtCore.QUrl.ParsingMode.TolerantMode`
        :description: QtCore/QUrl-setUrl-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.setUserInfo
        :args:
            str
            mode: :sip:ref:`~PyQt5.QtCore.QUrl.ParsingMode` = :sip:ref:`~PyQt5.QtCore.QUrl.ParsingMode.TolerantMode`
        :description: QtCore/QUrl-setUserInfo-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.setUserName
        :args:
            str
            mode: :sip:ref:`~PyQt5.QtCore.QUrl.ParsingMode` = :sip:ref:`~PyQt5.QtCore.QUrl.ParsingMode.DecodedMode`
        :description: QtCore/QUrl-setUserName-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.swap
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtCore/QUrl-swap-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.toAce
        :args:
            str
        :returns:
            :sip:ref:`~PyQt5.QtCore.QByteArray`
        :static:
        :description: QtCore/QUrl-toAce-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.toDisplayString
        :args:
            options: :sip:ref:`~PyQt5.QtCore.QUrl.FormattingOptions` = :sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOption.PrettyDecoded`
        :returns:
            str
        :description: QtCore/QUrl-toDisplayString-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.toEncoded
        :args:
            options: :sip:ref:`~PyQt5.QtCore.QUrl.FormattingOptions` = :sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOption.FullyEncoded`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QByteArray`
        :description: QtCore/QUrl-toEncoded-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.toLocalFile
        :returns:
            str
        :description: QtCore/QUrl-toLocalFile-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.toPercentEncoding
        :args:
            str
            exclude: Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray] = QByteArray()
            include: Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray] = QByteArray()
        :returns:
            :sip:ref:`~PyQt5.QtCore.QByteArray`
        :static:
        :description: QtCore/QUrl-toPercentEncoding-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.topLevelDomain
        :args:
            options: Union[:sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOptions`, :sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOption`] = :sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOption.FullyDecoded`
        :returns:
            str
        :description: QtCore/QUrl-topLevelDomain-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.toString
        :args:
            options: :sip:ref:`~PyQt5.QtCore.QUrl.FormattingOptions` = :sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOption.PrettyDecoded`
        :returns:
            str
        :description: QtCore/QUrl-toString-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.toStringList
        :args:
            Iterable[:sip:ref:`~PyQt5.QtCore.QUrl`]
            options: :sip:ref:`~PyQt5.QtCore.QUrl.FormattingOptions` = :sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOption.PrettyDecoded`
        :returns:
            List[str]
        :static:
        :description: QtCore/QUrl-toStringList-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.url
        :args:
            options: :sip:ref:`~PyQt5.QtCore.QUrl.FormattingOptions` = :sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOption.PrettyDecoded`
        :returns:
            str
        :description: QtCore/QUrl-url-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.userInfo
        :args:
            options: Union[:sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOptions`, :sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOption`] = :sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOption.PrettyDecoded`
        :returns:
            str
        :description: QtCore/QUrl-userInfo-f.rst

    .. sip:method:: PyQt5.QtCore.QUrl.userName
        :args:
            options: Union[:sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOptions`, :sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOption`] = :sip:ref:`~PyQt5.QtCore.QUrl.ComponentFormattingOption.FullyDecoded`
        :returns:
            str
        :description: QtCore/QUrl-userName-f.rst
