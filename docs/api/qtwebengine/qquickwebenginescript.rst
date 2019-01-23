:orphan:

.. sip:class:: PyQt5.QtWebEngine.QQuickWebEngineScript
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtWebEngine/QQuickWebEngineScript-c.rst

    .. sip:enum:: PyQt5.QtWebEngine.QQuickWebEngineScript.InjectionPoint
        :description: QtWebEngine/QQuickWebEngineScript-InjectionPoint-e.rst

        .. sip:enum-member:: PyQt5.QtWebEngine.QQuickWebEngineScript.InjectionPoint.Deferred
            :description: QtWebEngine/QQuickWebEngineScript-InjectionPoint-Deferred-v.rst

        .. sip:enum-member:: PyQt5.QtWebEngine.QQuickWebEngineScript.InjectionPoint.DocumentCreation
            :description: QtWebEngine/QQuickWebEngineScript-InjectionPoint-DocumentCreation-v.rst

        .. sip:enum-member:: PyQt5.QtWebEngine.QQuickWebEngineScript.InjectionPoint.DocumentReady
            :description: QtWebEngine/QQuickWebEngineScript-InjectionPoint-DocumentReady-v.rst

    .. sip:enum:: PyQt5.QtWebEngine.QQuickWebEngineScript.ScriptWorldId
        :description: QtWebEngine/QQuickWebEngineScript-ScriptWorldId-e.rst

        .. sip:enum-member:: PyQt5.QtWebEngine.QQuickWebEngineScript.ScriptWorldId.ApplicationWorld
            :description: QtWebEngine/QQuickWebEngineScript-ScriptWorldId-ApplicationWorld-v.rst

        .. sip:enum-member:: PyQt5.QtWebEngine.QQuickWebEngineScript.ScriptWorldId.MainWorld
            :description: QtWebEngine/QQuickWebEngineScript-ScriptWorldId-MainWorld-v.rst

        .. sip:enum-member:: PyQt5.QtWebEngine.QQuickWebEngineScript.ScriptWorldId.UserWorld
            :description: QtWebEngine/QQuickWebEngineScript-ScriptWorldId-UserWorld-v.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineScript.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtWebEngine/QQuickWebEngineScript-__init__-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineScript.injectionPoint
        :returns:
            :sip:ref:`~PyQt5.QtWebEngine.QQuickWebEngineScript.InjectionPoint`
        :description: QtWebEngine/QQuickWebEngineScript-injectionPoint-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineScript.name
        :returns:
            str
        :description: QtWebEngine/QQuickWebEngineScript-name-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineScript.runOnSubframes
        :returns:
            bool
        :description: QtWebEngine/QQuickWebEngineScript-runOnSubframes-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineScript.setInjectionPoint
        :args:
            :sip:ref:`~PyQt5.QtWebEngine.QQuickWebEngineScript.InjectionPoint`
        :description: QtWebEngine/QQuickWebEngineScript-setInjectionPoint-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineScript.setName
        :args:
            str
        :description: QtWebEngine/QQuickWebEngineScript-setName-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineScript.setRunOnSubframes
        :args:
            bool
        :description: QtWebEngine/QQuickWebEngineScript-setRunOnSubframes-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineScript.setSourceCode
        :args:
            str
        :description: QtWebEngine/QQuickWebEngineScript-setSourceCode-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineScript.setSourceUrl
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtWebEngine/QQuickWebEngineScript-setSourceUrl-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineScript.setWorldId
        :args:
            :sip:ref:`~PyQt5.QtWebEngine.QQuickWebEngineScript.ScriptWorldId`
        :description: QtWebEngine/QQuickWebEngineScript-setWorldId-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineScript.sourceCode
        :returns:
            str
        :description: QtWebEngine/QQuickWebEngineScript-sourceCode-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineScript.sourceUrl
        :returns:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtWebEngine/QQuickWebEngineScript-sourceUrl-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineScript.timerEvent
        :args:
            :sip:ref:`~PyQt5.QtCore.QTimerEvent`
        :description: QtWebEngine/QQuickWebEngineScript-timerEvent-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineScript.toString
        :returns:
            str
        :description: QtWebEngine/QQuickWebEngineScript-toString-f.rst

    .. sip:method:: PyQt5.QtWebEngine.QQuickWebEngineScript.worldId
        :returns:
            :sip:ref:`~PyQt5.QtWebEngine.QQuickWebEngineScript.ScriptWorldId`
        :description: QtWebEngine/QQuickWebEngineScript-worldId-f.rst

    .. sip:signal:: PyQt5.QtWebEngine.QQuickWebEngineScript.injectionPointChanged
        :args:
            :sip:ref:`~PyQt5.QtWebEngine.QQuickWebEngineScript.InjectionPoint`
        :description: QtWebEngine/QQuickWebEngineScript-injectionPointChanged-s.rst

    .. sip:signal:: PyQt5.QtWebEngine.QQuickWebEngineScript.nameChanged
        :args:
            str
        :description: QtWebEngine/QQuickWebEngineScript-nameChanged-s.rst

    .. sip:signal:: PyQt5.QtWebEngine.QQuickWebEngineScript.runOnSubframesChanged
        :args:
            bool
        :description: QtWebEngine/QQuickWebEngineScript-runOnSubframesChanged-s.rst

    .. sip:signal:: PyQt5.QtWebEngine.QQuickWebEngineScript.sourceCodeChanged
        :args:
            str
        :description: QtWebEngine/QQuickWebEngineScript-sourceCodeChanged-s.rst

    .. sip:signal:: PyQt5.QtWebEngine.QQuickWebEngineScript.sourceUrlChanged
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtWebEngine/QQuickWebEngineScript-sourceUrlChanged-s.rst

    .. sip:signal:: PyQt5.QtWebEngine.QQuickWebEngineScript.worldIdChanged
        :args:
            :sip:ref:`~PyQt5.QtWebEngine.QQuickWebEngineScript.ScriptWorldId`
        :description: QtWebEngine/QQuickWebEngineScript-worldIdChanged-s.rst
