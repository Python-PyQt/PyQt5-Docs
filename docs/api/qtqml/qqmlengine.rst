:orphan:

.. sip:class:: PyQt5.QtQml.QQmlEngine
    :inherits: :sip:ref:`~PyQt5.QtQml.QJSEngine`
    :description: QtQml/QQmlEngine-c.rst

    .. sip:enum:: PyQt5.QtQml.QQmlEngine.ObjectOwnership
        :description: QtQml/QQmlEngine-ObjectOwnership-e.rst

        .. sip:enum-member:: PyQt5.QtQml.QQmlEngine.ObjectOwnership.CppOwnership
            :description: QtQml/QQmlEngine-ObjectOwnership-CppOwnership-v.rst

        .. sip:enum-member:: PyQt5.QtQml.QQmlEngine.ObjectOwnership.JavaScriptOwnership
            :description: QtQml/QQmlEngine-ObjectOwnership-JavaScriptOwnership-v.rst

    .. sip:method:: PyQt5.QtQml.QQmlEngine.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtQml/QQmlEngine-__init__-f.rst

    .. sip:method:: PyQt5.QtQml.QQmlEngine.addImageProvider
        :args:
            str
            :sip:ref:`~PyQt5.QtQml.QQmlImageProviderBase`
        :description: QtQml/QQmlEngine-addImageProvider-f.rst

    .. sip:method:: PyQt5.QtQml.QQmlEngine.addImportPath
        :args:
            str
        :description: QtQml/QQmlEngine-addImportPath-f.rst

    .. sip:method:: PyQt5.QtQml.QQmlEngine.addNamedBundle
        :args:
            str
            str
        :returns:
            bool
        :description: QtQml/QQmlEngine-addNamedBundle-f.rst

    .. sip:method:: PyQt5.QtQml.QQmlEngine.addPluginPath
        :args:
            str
        :description: QtQml/QQmlEngine-addPluginPath-f.rst

    .. sip:method:: PyQt5.QtQml.QQmlEngine.baseUrl
        :returns:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtQml/QQmlEngine-baseUrl-f.rst

    .. sip:method:: PyQt5.QtQml.QQmlEngine.clearComponentCache
        :description: QtQml/QQmlEngine-clearComponentCache-f.rst

    .. sip:method:: PyQt5.QtQml.QQmlEngine.contextForObject
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
        :returns:
            :sip:ref:`~PyQt5.QtQml.QQmlContext`
        :static:
        :description: QtQml/QQmlEngine-contextForObject-f.rst

    .. sip:method:: PyQt5.QtQml.QQmlEngine.event
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtQml/QQmlEngine-event-f.rst

    .. sip:method:: PyQt5.QtQml.QQmlEngine.imageProvider
        :args:
            str
        :returns:
            :sip:ref:`~PyQt5.QtQml.QQmlImageProviderBase`
        :description: QtQml/QQmlEngine-imageProvider-f.rst

    .. sip:method:: PyQt5.QtQml.QQmlEngine.importPathList
        :returns:
            List[str]
        :description: QtQml/QQmlEngine-importPathList-f.rst

    .. sip:method:: PyQt5.QtQml.QQmlEngine.importPlugin
        :args:
            str
            str
            Iterable[:sip:ref:`~PyQt5.QtQml.QQmlError`]
        :returns:
            bool
        :description: QtQml/QQmlEngine-importPlugin-f.rst

    .. sip:method:: PyQt5.QtQml.QQmlEngine.incubationController
        :returns:
            :sip:ref:`~PyQt5.QtQml.QQmlIncubationController`
        :description: QtQml/QQmlEngine-incubationController-f.rst

    .. sip:method:: PyQt5.QtQml.QQmlEngine.networkAccessManager
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager`
        :description: QtQml/QQmlEngine-networkAccessManager-f.rst

    .. sip:method:: PyQt5.QtQml.QQmlEngine.networkAccessManagerFactory
        :returns:
            :sip:ref:`~PyQt5.QtQml.QQmlNetworkAccessManagerFactory`
        :description: QtQml/QQmlEngine-networkAccessManagerFactory-f.rst

    .. sip:method:: PyQt5.QtQml.QQmlEngine.objectOwnership
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
        :returns:
            :sip:ref:`~PyQt5.QtQml.QQmlEngine.ObjectOwnership`
        :static:
        :description: QtQml/QQmlEngine-objectOwnership-f.rst

    .. sip:method:: PyQt5.QtQml.QQmlEngine.offlineStorageDatabaseFilePath
        :args:
            str
        :returns:
            str
        :description: QtQml/QQmlEngine-offlineStorageDatabaseFilePath-f.rst

    .. sip:method:: PyQt5.QtQml.QQmlEngine.offlineStoragePath
        :returns:
            str
        :description: QtQml/QQmlEngine-offlineStoragePath-f.rst

    .. sip:method:: PyQt5.QtQml.QQmlEngine.outputWarningsToStandardError
        :returns:
            bool
        :description: QtQml/QQmlEngine-outputWarningsToStandardError-f.rst

    .. sip:method:: PyQt5.QtQml.QQmlEngine.pluginPathList
        :returns:
            List[str]
        :description: QtQml/QQmlEngine-pluginPathList-f.rst

    .. sip:method:: PyQt5.QtQml.QQmlEngine.removeImageProvider
        :args:
            str
        :description: QtQml/QQmlEngine-removeImageProvider-f.rst

    .. sip:method:: PyQt5.QtQml.QQmlEngine.retranslate
        :description: QtQml/QQmlEngine-retranslate-f.rst

    .. sip:method:: PyQt5.QtQml.QQmlEngine.rootContext
        :returns:
            :sip:ref:`~PyQt5.QtQml.QQmlContext`
        :description: QtQml/QQmlEngine-rootContext-f.rst

    .. sip:method:: PyQt5.QtQml.QQmlEngine.setBaseUrl
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtQml/QQmlEngine-setBaseUrl-f.rst

    .. sip:method:: PyQt5.QtQml.QQmlEngine.setContextForObject
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
            :sip:ref:`~PyQt5.QtQml.QQmlContext`
        :static:
        :description: QtQml/QQmlEngine-setContextForObject-f.rst

    .. sip:method:: PyQt5.QtQml.QQmlEngine.setImportPathList
        :args:
            Iterable[str]
        :description: QtQml/QQmlEngine-setImportPathList-f.rst

    .. sip:method:: PyQt5.QtQml.QQmlEngine.setIncubationController
        :args:
            :sip:ref:`~PyQt5.QtQml.QQmlIncubationController`
        :description: QtQml/QQmlEngine-setIncubationController-f.rst

    .. sip:method:: PyQt5.QtQml.QQmlEngine.setNetworkAccessManagerFactory
        :args:
            :sip:ref:`~PyQt5.QtQml.QQmlNetworkAccessManagerFactory`
        :description: QtQml/QQmlEngine-setNetworkAccessManagerFactory-f.rst

    .. sip:method:: PyQt5.QtQml.QQmlEngine.setObjectOwnership
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
            :sip:ref:`~PyQt5.QtQml.QQmlEngine.ObjectOwnership`
        :static:
        :description: QtQml/QQmlEngine-setObjectOwnership-f.rst

    .. sip:method:: PyQt5.QtQml.QQmlEngine.setOfflineStoragePath
        :args:
            str
        :description: QtQml/QQmlEngine-setOfflineStoragePath-f.rst

    .. sip:method:: PyQt5.QtQml.QQmlEngine.setOutputWarningsToStandardError
        :args:
            bool
        :description: QtQml/QQmlEngine-setOutputWarningsToStandardError-f.rst

    .. sip:method:: PyQt5.QtQml.QQmlEngine.setPluginPathList
        :args:
            Iterable[str]
        :description: QtQml/QQmlEngine-setPluginPathList-f.rst

    .. sip:method:: PyQt5.QtQml.QQmlEngine.singletonInstance
        :args:
            int
        :returns:
            :sip:ref:`~PyQt5.QtCore.QObject`
        :description: QtQml/QQmlEngine-singletonInstance-f.rst

    .. sip:method:: PyQt5.QtQml.QQmlEngine.trimComponentCache
        :description: QtQml/QQmlEngine-trimComponentCache-f.rst

    .. sip:signal:: PyQt5.QtQml.QQmlEngine.exit
        :args:
            int
        :description: QtQml/QQmlEngine-exit-s.rst

    .. sip:signal:: PyQt5.QtQml.QQmlEngine.quit
        :description: QtQml/QQmlEngine-quit-s.rst

    .. sip:signal:: PyQt5.QtQml.QQmlEngine.warnings
        :args:
            Iterable[:sip:ref:`~PyQt5.QtQml.QQmlError`]
        :description: QtQml/QQmlEngine-warnings-s.rst
