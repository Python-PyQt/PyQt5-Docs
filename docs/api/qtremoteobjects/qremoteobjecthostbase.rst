:orphan:

.. sip:class:: PyQt5.QtRemoteObjects.QRemoteObjectHostBase
    :inherits: :sip:ref:`~PyQt5.QtRemoteObjects.QRemoteObjectNode`
    :description: QtRemoteObjects/QRemoteObjectHostBase-c.rst

    .. sip:enum:: PyQt5.QtRemoteObjects.QRemoteObjectHostBase.AllowedSchemas
        :description: QtRemoteObjects/QRemoteObjectHostBase-AllowedSchemas-e.rst

        .. sip:enum-member:: PyQt5.QtRemoteObjects.QRemoteObjectHostBase.AllowedSchemas.AllowExternalRegistration
            :description: QtRemoteObjects/QRemoteObjectHostBase-AllowedSchemas-AllowExternalRegistration-v.rst

        .. sip:enum-member:: PyQt5.QtRemoteObjects.QRemoteObjectHostBase.AllowedSchemas.BuiltInSchemasOnly
            :description: QtRemoteObjects/QRemoteObjectHostBase-AllowedSchemas-BuiltInSchemasOnly-v.rst

    .. sip:method:: PyQt5.QtRemoteObjects.QRemoteObjectHostBase.addHostSideConnection
        :args:
            :sip:ref:`~PyQt5.QtCore.QIODevice`
        :description: QtRemoteObjects/QRemoteObjectHostBase-addHostSideConnection-f.rst

    .. sip:method:: PyQt5.QtRemoteObjects.QRemoteObjectHostBase.disableRemoting
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
        :returns:
            bool
        :description: QtRemoteObjects/QRemoteObjectHostBase-disableRemoting-f.rst

    .. sip:method:: PyQt5.QtRemoteObjects.QRemoteObjectHostBase.enableRemoting
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
            name: str = ''
        :returns:
            bool
        :description: QtRemoteObjects/QRemoteObjectHostBase-enableRemoting-f.rst

    .. sip:method:: PyQt5.QtRemoteObjects.QRemoteObjectHostBase.enableRemoting
        :args:
            :sip:ref:`~PyQt5.QtCore.QAbstractItemModel`
            str
            Iterable[int]
            selectionModel: :sip:ref:`~PyQt5.QtCore.QItemSelectionModel` = None
        :returns:
            bool
        :description: QtRemoteObjects/QRemoteObjectHostBase-enableRemoting-f-1.rst

    .. sip:method:: PyQt5.QtRemoteObjects.QRemoteObjectHostBase.proxy
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
            hostUrl: :sip:ref:`~PyQt5.QtCore.QUrl` = QUrl()
        :returns:
            bool
        :description: QtRemoteObjects/QRemoteObjectHostBase-proxy-f.rst

    .. sip:method:: PyQt5.QtRemoteObjects.QRemoteObjectHostBase.reverseProxy
        :returns:
            bool
        :description: QtRemoteObjects/QRemoteObjectHostBase-reverseProxy-f.rst

    .. sip:method:: PyQt5.QtRemoteObjects.QRemoteObjectHostBase.setName
        :args:
            str
        :description: QtRemoteObjects/QRemoteObjectHostBase-setName-f.rst
