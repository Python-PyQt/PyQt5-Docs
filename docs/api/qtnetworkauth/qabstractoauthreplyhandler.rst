:orphan:

.. sip:class:: PyQt5.QtNetworkAuth.QAbstractOAuthReplyHandler
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtNetworkAuth/QAbstractOAuthReplyHandler-c.rst

    .. sip:method:: PyQt5.QtNetworkAuth.QAbstractOAuthReplyHandler.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtNetworkAuth/QAbstractOAuthReplyHandler-__init__-f.rst

    .. sip:method:: PyQt5.QtNetworkAuth.QAbstractOAuthReplyHandler.callback
        :returns:
            str
        :description: QtNetworkAuth/QAbstractOAuthReplyHandler-callback-f.rst

    .. sip:method:: PyQt5.QtNetworkAuth.QAbstractOAuthReplyHandler.networkReplyFinished
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkReply`
        :description: QtNetworkAuth/QAbstractOAuthReplyHandler-networkReplyFinished-f.rst

    .. sip:signal:: PyQt5.QtNetworkAuth.QAbstractOAuthReplyHandler.callbackDataReceived
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :description: QtNetworkAuth/QAbstractOAuthReplyHandler-callbackDataReceived-s.rst

    .. sip:signal:: PyQt5.QtNetworkAuth.QAbstractOAuthReplyHandler.callbackReceived
        :args:
            Dict[str, Any]
        :description: QtNetworkAuth/QAbstractOAuthReplyHandler-callbackReceived-s.rst

    .. sip:signal:: PyQt5.QtNetworkAuth.QAbstractOAuthReplyHandler.replyDataReceived
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :description: QtNetworkAuth/QAbstractOAuthReplyHandler-replyDataReceived-s.rst

    .. sip:signal:: PyQt5.QtNetworkAuth.QAbstractOAuthReplyHandler.tokensReceived
        :args:
            Dict[str, Any]
        :description: QtNetworkAuth/QAbstractOAuthReplyHandler-tokensReceived-s.rst
