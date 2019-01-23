:orphan:

.. sip:class:: PyQt5.QtWebEngine.QQuickWebEngineProfile
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtWebEngine/QQuickWebEngineProfile-c.rst

    .. sip:enum:: PyQt5.QtWebEngine.QQuickWebEngineProfile.HttpCacheType
        :description: QtWebEngine/QQuickWebEngineProfile-HttpCacheType-e.rst

        .. sip:enum-member:: PyQt5.QtWebEngine.QQuickWebEngineProfile.HttpCacheType.DiskHttpCache
            :description: QtWebEngine/QQuickWebEngineProfile-HttpCacheType-DiskHttpCache-v.rst

        .. sip:enum-member:: PyQt5.QtWebEngine.QQuickWebEngineProfile.HttpCacheType.MemoryHttpCache
            :description: QtWebEngine/QQuickWebEngineProfile-HttpCacheType-MemoryHttpCache-v.rst

        .. sip:enum-member:: PyQt5.QtWebEngine.QQuickWebEngineProfile.HttpCacheType.NoCache
            :description: QtWebEngine/QQuickWebEngineProfile-HttpCacheType-NoCache-v.rst

    .. sip:enum:: PyQt5.QtWebEngine.QQuickWebEngineProfile.PersistentCookiesPolicy
        :description: QtWebEngine/QQuickWebEngineProfile-PersistentCookiesPolicy-e.rst

        .. sip:enum-member:: PyQt5.QtWebEngine.QQuickWebEngineProfile.PersistentCookiesPolicy.AllowPersistentCookies
            :description: QtWebEngine/QQuickWebEngineProfile-PersistentCookiesPolicy-AllowPersistentCookies-v.rst

        .. sip:enum-member:: PyQt5.QtWebEngine.QQuickWebEngineProfile.PersistentCookiesPolicy.ForcePersistentCookies
            :description: QtWebEngine/QQuickWebEngineProfile-PersistentCookiesPolicy-ForcePersistentCookies-v.rst

        .. sip:enum-member:: PyQt5.QtWebEngine.QQuickWebEngineProfile.PersistentCookiesPolicy.NoPersistentCookies
            :description: QtWebEngine/QQuickWebEngineProfile-PersistentCookiesPolicy-NoPersistentCookies-v.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineProfile.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtWebEngine/QQuickWebEngineProfile-__init__-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineProfile.cachePath
        :returns:
            str
        :description: QtWebEngine/QQuickWebEngineProfile-cachePath-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineProfile.clearHttpCache
        :description: QtWebEngine/QQuickWebEngineProfile-clearHttpCache-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineProfile.cookieStore
        :returns:
            :sip:ref:`~PyQt5.QtWebEngineCore.QWebEngineCookieStore`
        :description: QtWebEngine/QQuickWebEngineProfile-cookieStore-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineProfile.defaultProfile
        :returns:
            :sip:ref:`~PyQt5.QtWebEngine.QQuickWebEngineProfile`
        :static:
        :description: QtWebEngine/QQuickWebEngineProfile-defaultProfile-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineProfile.httpAcceptLanguage
        :returns:
            str
        :description: QtWebEngine/QQuickWebEngineProfile-httpAcceptLanguage-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineProfile.httpCacheMaximumSize
        :returns:
            int
        :description: QtWebEngine/QQuickWebEngineProfile-httpCacheMaximumSize-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineProfile.httpCacheType
        :returns:
            :sip:ref:`~PyQt5.QtWebEngine.QQuickWebEngineProfile.HttpCacheType`
        :description: QtWebEngine/QQuickWebEngineProfile-httpCacheType-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineProfile.httpUserAgent
        :returns:
            str
        :description: QtWebEngine/QQuickWebEngineProfile-httpUserAgent-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineProfile.installUrlSchemeHandler
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
            :sip:ref:`~PyQt5.QtWebEngineCore.QWebEngineUrlSchemeHandler`
        :description: QtWebEngine/QQuickWebEngineProfile-installUrlSchemeHandler-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineProfile.isOffTheRecord
        :returns:
            bool
        :description: QtWebEngine/QQuickWebEngineProfile-isOffTheRecord-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineProfile.isSpellCheckEnabled
        :returns:
            bool
        :description: QtWebEngine/QQuickWebEngineProfile-isSpellCheckEnabled-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineProfile.persistentCookiesPolicy
        :returns:
            :sip:ref:`~PyQt5.QtWebEngine.QQuickWebEngineProfile.PersistentCookiesPolicy`
        :description: QtWebEngine/QQuickWebEngineProfile-persistentCookiesPolicy-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineProfile.persistentStoragePath
        :returns:
            str
        :description: QtWebEngine/QQuickWebEngineProfile-persistentStoragePath-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineProfile.removeAllUrlSchemeHandlers
        :description: QtWebEngine/QQuickWebEngineProfile-removeAllUrlSchemeHandlers-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineProfile.removeUrlScheme
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :description: QtWebEngine/QQuickWebEngineProfile-removeUrlScheme-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineProfile.removeUrlSchemeHandler
        :args:
            :sip:ref:`~PyQt5.QtWebEngineCore.QWebEngineUrlSchemeHandler`
        :description: QtWebEngine/QQuickWebEngineProfile-removeUrlSchemeHandler-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineProfile.setCachePath
        :args:
            str
        :description: QtWebEngine/QQuickWebEngineProfile-setCachePath-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineProfile.setHttpAcceptLanguage
        :args:
            str
        :description: QtWebEngine/QQuickWebEngineProfile-setHttpAcceptLanguage-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineProfile.setHttpCacheMaximumSize
        :args:
            int
        :description: QtWebEngine/QQuickWebEngineProfile-setHttpCacheMaximumSize-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineProfile.setHttpCacheType
        :args:
            :sip:ref:`~PyQt5.QtWebEngine.QQuickWebEngineProfile.HttpCacheType`
        :description: QtWebEngine/QQuickWebEngineProfile-setHttpCacheType-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineProfile.setHttpUserAgent
        :args:
            str
        :description: QtWebEngine/QQuickWebEngineProfile-setHttpUserAgent-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineProfile.setOffTheRecord
        :args:
            bool
        :description: QtWebEngine/QQuickWebEngineProfile-setOffTheRecord-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineProfile.setPersistentCookiesPolicy
        :args:
            :sip:ref:`~PyQt5.QtWebEngine.QQuickWebEngineProfile.PersistentCookiesPolicy`
        :description: QtWebEngine/QQuickWebEngineProfile-setPersistentCookiesPolicy-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineProfile.setPersistentStoragePath
        :args:
            str
        :description: QtWebEngine/QQuickWebEngineProfile-setPersistentStoragePath-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineProfile.setRequestInterceptor
        :args:
            :sip:ref:`~PyQt5.QtWebEngineCore.QWebEngineUrlRequestInterceptor`
        :description: QtWebEngine/QQuickWebEngineProfile-setRequestInterceptor-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineProfile.setSpellCheckEnabled
        :args:
            bool
        :description: QtWebEngine/QQuickWebEngineProfile-setSpellCheckEnabled-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineProfile.setSpellCheckLanguages
        :args:
            Iterable[str]
        :description: QtWebEngine/QQuickWebEngineProfile-setSpellCheckLanguages-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineProfile.setStorageName
        :args:
            str
        :description: QtWebEngine/QQuickWebEngineProfile-setStorageName-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineProfile.spellCheckLanguages
        :returns:
            List[str]
        :description: QtWebEngine/QQuickWebEngineProfile-spellCheckLanguages-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineProfile.storageName
        :returns:
            str
        :description: QtWebEngine/QQuickWebEngineProfile-storageName-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineProfile.urlSchemeHandler
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :returns:
            :sip:ref:`~PyQt5.QtWebEngineCore.QWebEngineUrlSchemeHandler`
        :description: QtWebEngine/QQuickWebEngineProfile-urlSchemeHandler-f.rst

    .. sip:signal:: PyQt5.QtWebEngine.QQuickWebEngineProfile.cachePathChanged
        :description: QtWebEngine/QQuickWebEngineProfile-cachePathChanged-s.rst

    .. sip:signal:: PyQt5.QtWebEngine.QQuickWebEngineProfile.httpAcceptLanguageChanged
        :description: QtWebEngine/QQuickWebEngineProfile-httpAcceptLanguageChanged-s.rst

    .. sip:signal:: PyQt5.QtWebEngine.QQuickWebEngineProfile.httpCacheMaximumSizeChanged
        :description: QtWebEngine/QQuickWebEngineProfile-httpCacheMaximumSizeChanged-s.rst

    .. sip:signal:: PyQt5.QtWebEngine.QQuickWebEngineProfile.httpCacheTypeChanged
        :description: QtWebEngine/QQuickWebEngineProfile-httpCacheTypeChanged-s.rst

    .. sip:signal:: PyQt5.QtWebEngine.QQuickWebEngineProfile.httpUserAgentChanged
        :description: QtWebEngine/QQuickWebEngineProfile-httpUserAgentChanged-s.rst

    .. sip:signal:: PyQt5.QtWebEngine.QQuickWebEngineProfile.offTheRecordChanged
        :description: QtWebEngine/QQuickWebEngineProfile-offTheRecordChanged-s.rst

    .. sip:signal:: PyQt5.QtWebEngine.QQuickWebEngineProfile.persistentCookiesPolicyChanged
        :description: QtWebEngine/QQuickWebEngineProfile-persistentCookiesPolicyChanged-s.rst

    .. sip:signal:: PyQt5.QtWebEngine.QQuickWebEngineProfile.persistentStoragePathChanged
        :description: QtWebEngine/QQuickWebEngineProfile-persistentStoragePathChanged-s.rst

    .. sip:signal:: PyQt5.QtWebEngine.QQuickWebEngineProfile.spellCheckEnabledChanged
        :description: QtWebEngine/QQuickWebEngineProfile-spellCheckEnabledChanged-s.rst

    .. sip:signal:: PyQt5.QtWebEngine.QQuickWebEngineProfile.spellCheckLanguagesChanged
        :description: QtWebEngine/QQuickWebEngineProfile-spellCheckLanguagesChanged-s.rst

    .. sip:signal:: PyQt5.QtWebEngine.QQuickWebEngineProfile.storageNameChanged
        :description: QtWebEngine/QQuickWebEngineProfile-storageNameChanged-s.rst
