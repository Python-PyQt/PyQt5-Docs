:orphan:

.. sip:class:: PyQt5.QtWebEngineWidgets.QWebEngineProfile
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtWebEngineWidgets/QWebEngineProfile-c.rst

    .. sip:enum:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.HttpCacheType
        :description: QtWebEngineWidgets/QWebEngineProfile-HttpCacheType-e.rst

        .. sip:enum-member:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.HttpCacheType.DiskHttpCache
            :description: QtWebEngineWidgets/QWebEngineProfile-HttpCacheType-DiskHttpCache-v.rst

        .. sip:enum-member:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.HttpCacheType.MemoryHttpCache
            :description: QtWebEngineWidgets/QWebEngineProfile-HttpCacheType-MemoryHttpCache-v.rst

        .. sip:enum-member:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.HttpCacheType.NoCache
            :description: QtWebEngineWidgets/QWebEngineProfile-HttpCacheType-NoCache-v.rst

    .. sip:enum:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.PersistentCookiesPolicy
        :description: QtWebEngineWidgets/QWebEngineProfile-PersistentCookiesPolicy-e.rst

        .. sip:enum-member:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.PersistentCookiesPolicy.AllowPersistentCookies
            :description: QtWebEngineWidgets/QWebEngineProfile-PersistentCookiesPolicy-AllowPersistentCookies-v.rst

        .. sip:enum-member:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.PersistentCookiesPolicy.ForcePersistentCookies
            :description: QtWebEngineWidgets/QWebEngineProfile-PersistentCookiesPolicy-ForcePersistentCookies-v.rst

        .. sip:enum-member:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.PersistentCookiesPolicy.NoPersistentCookies
            :description: QtWebEngineWidgets/QWebEngineProfile-PersistentCookiesPolicy-NoPersistentCookies-v.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtWebEngineWidgets/QWebEngineProfile-__init__-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.__init__
        :args:
            str
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtWebEngineWidgets/QWebEngineProfile-__init__-f-1.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.cachePath
        :returns:
            str
        :description: QtWebEngineWidgets/QWebEngineProfile-cachePath-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.clearAllVisitedLinks
        :description: QtWebEngineWidgets/QWebEngineProfile-clearAllVisitedLinks-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.clearHttpCache
        :description: QtWebEngineWidgets/QWebEngineProfile-clearHttpCache-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.clearVisitedLinks
        :args:
            Iterable[:sip:ref:`~PyQt5.QtCore.QUrl`]
        :description: QtWebEngineWidgets/QWebEngineProfile-clearVisitedLinks-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.clientCertificateStore
        :returns:
            :sip:ref:`~PyQt5.QtWebEngineCore.QWebEngineClientCertificateStore`
        :description: QtWebEngineWidgets/QWebEngineProfile-clientCertificateStore-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.cookieStore
        :returns:
            :sip:ref:`~PyQt5.QtWebEngineCore.QWebEngineCookieStore`
        :description: QtWebEngineWidgets/QWebEngineProfile-cookieStore-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.defaultProfile
        :returns:
            :sip:ref:`~PyQt5.QtWebEngineWidgets.QWebEngineProfile`
        :static:
        :description: QtWebEngineWidgets/QWebEngineProfile-defaultProfile-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.downloadPath
        :returns:
            str
        :description: QtWebEngineWidgets/QWebEngineProfile-downloadPath-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.httpAcceptLanguage
        :returns:
            str
        :description: QtWebEngineWidgets/QWebEngineProfile-httpAcceptLanguage-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.httpCacheMaximumSize
        :returns:
            int
        :description: QtWebEngineWidgets/QWebEngineProfile-httpCacheMaximumSize-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.httpCacheType
        :returns:
            :sip:ref:`~PyQt5.QtWebEngineWidgets.QWebEngineProfile.HttpCacheType`
        :description: QtWebEngineWidgets/QWebEngineProfile-httpCacheType-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.httpUserAgent
        :returns:
            str
        :description: QtWebEngineWidgets/QWebEngineProfile-httpUserAgent-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.installUrlSchemeHandler
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
            :sip:ref:`~PyQt5.QtWebEngineCore.QWebEngineUrlSchemeHandler`
        :description: QtWebEngineWidgets/QWebEngineProfile-installUrlSchemeHandler-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.isOffTheRecord
        :returns:
            bool
        :description: QtWebEngineWidgets/QWebEngineProfile-isOffTheRecord-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.isSpellCheckEnabled
        :returns:
            bool
        :description: QtWebEngineWidgets/QWebEngineProfile-isSpellCheckEnabled-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.isUsedForGlobalCertificateVerification
        :returns:
            bool
        :description: QtWebEngineWidgets/QWebEngineProfile-isUsedForGlobalCertificateVerification-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.persistentCookiesPolicy
        :returns:
            :sip:ref:`~PyQt5.QtWebEngineWidgets.QWebEngineProfile.PersistentCookiesPolicy`
        :description: QtWebEngineWidgets/QWebEngineProfile-persistentCookiesPolicy-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.persistentStoragePath
        :returns:
            str
        :description: QtWebEngineWidgets/QWebEngineProfile-persistentStoragePath-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.removeAllUrlSchemeHandlers
        :description: QtWebEngineWidgets/QWebEngineProfile-removeAllUrlSchemeHandlers-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.removeUrlScheme
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :description: QtWebEngineWidgets/QWebEngineProfile-removeUrlScheme-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.removeUrlSchemeHandler
        :args:
            :sip:ref:`~PyQt5.QtWebEngineCore.QWebEngineUrlSchemeHandler`
        :description: QtWebEngineWidgets/QWebEngineProfile-removeUrlSchemeHandler-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.scripts
        :returns:
            :sip:ref:`~PyQt5.QtWebEngineWidgets.QWebEngineScriptCollection`
        :description: QtWebEngineWidgets/QWebEngineProfile-scripts-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.setCachePath
        :args:
            str
        :description: QtWebEngineWidgets/QWebEngineProfile-setCachePath-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.setDownloadPath
        :args:
            str
        :description: QtWebEngineWidgets/QWebEngineProfile-setDownloadPath-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.setHttpAcceptLanguage
        :args:
            str
        :description: QtWebEngineWidgets/QWebEngineProfile-setHttpAcceptLanguage-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.setHttpCacheMaximumSize
        :args:
            int
        :description: QtWebEngineWidgets/QWebEngineProfile-setHttpCacheMaximumSize-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.setHttpCacheType
        :args:
            :sip:ref:`~PyQt5.QtWebEngineWidgets.QWebEngineProfile.HttpCacheType`
        :description: QtWebEngineWidgets/QWebEngineProfile-setHttpCacheType-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.setHttpUserAgent
        :args:
            str
        :description: QtWebEngineWidgets/QWebEngineProfile-setHttpUserAgent-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.setNotificationPresenter
        :args:
            Callable[[:sip:ref:`~PyQt5.QtWebEngineCore.QWebEngineNotification`], None]
        :description: QtWebEngineWidgets/QWebEngineProfile-setNotificationPresenter-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.setPersistentCookiesPolicy
        :args:
            :sip:ref:`~PyQt5.QtWebEngineWidgets.QWebEngineProfile.PersistentCookiesPolicy`
        :description: QtWebEngineWidgets/QWebEngineProfile-setPersistentCookiesPolicy-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.setPersistentStoragePath
        :args:
            str
        :description: QtWebEngineWidgets/QWebEngineProfile-setPersistentStoragePath-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.setRequestInterceptor
        :args:
            :sip:ref:`~PyQt5.QtWebEngineCore.QWebEngineUrlRequestInterceptor`
        :description: QtWebEngineWidgets/QWebEngineProfile-setRequestInterceptor-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.setSpellCheckEnabled
        :args:
            bool
        :description: QtWebEngineWidgets/QWebEngineProfile-setSpellCheckEnabled-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.setSpellCheckLanguages
        :args:
            Iterable[str]
        :description: QtWebEngineWidgets/QWebEngineProfile-setSpellCheckLanguages-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.settings
        :returns:
            :sip:ref:`~PyQt5.QtWebEngineWidgets.QWebEngineSettings`
        :description: QtWebEngineWidgets/QWebEngineProfile-settings-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.setUrlRequestInterceptor
        :args:
            :sip:ref:`~PyQt5.QtWebEngineCore.QWebEngineUrlRequestInterceptor`
        :description: QtWebEngineWidgets/QWebEngineProfile-setUrlRequestInterceptor-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.setUseForGlobalCertificateVerification
        :args:
            enabled: bool = True
        :description: QtWebEngineWidgets/QWebEngineProfile-setUseForGlobalCertificateVerification-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.spellCheckLanguages
        :returns:
            List[str]
        :description: QtWebEngineWidgets/QWebEngineProfile-spellCheckLanguages-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.storageName
        :returns:
            str
        :description: QtWebEngineWidgets/QWebEngineProfile-storageName-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.urlSchemeHandler
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :returns:
            :sip:ref:`~PyQt5.QtWebEngineCore.QWebEngineUrlSchemeHandler`
        :description: QtWebEngineWidgets/QWebEngineProfile-urlSchemeHandler-f.rst

    .. sip:method:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.visitedLinksContainsUrl
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :returns:
            bool
        :description: QtWebEngineWidgets/QWebEngineProfile-visitedLinksContainsUrl-f.rst

    .. sip:signal:: PyQt5.QtWebEngineWidgets.QWebEngineProfile.downloadRequested
        :args:
            :sip:ref:`~PyQt5.QtWebEngineWidgets.QWebEngineDownloadItem`
        :description: QtWebEngineWidgets/QWebEngineProfile-downloadRequested-s.rst
