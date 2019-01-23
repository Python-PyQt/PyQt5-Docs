:orphan:

.. sip:class:: PyQt5.QtWebEngineCore.QWebEngineHttpRequest
    :description: QtWebEngineCore/QWebEngineHttpRequest-c.rst

    .. sip:enum:: PyQt5.QtWebEngineCore.QWebEngineHttpRequest.Method
        :description: QtWebEngineCore/QWebEngineHttpRequest-Method-e.rst

        .. sip:enum-member:: PyQt5.QtWebEngineCore.QWebEngineHttpRequest.Method.Get
            :description: QtWebEngineCore/QWebEngineHttpRequest-Method-Get-v.rst

        .. sip:enum-member:: PyQt5.QtWebEngineCore.QWebEngineHttpRequest.Method.Post
            :description: QtWebEngineCore/QWebEngineHttpRequest-Method-Post-v.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineHttpRequest.__init__
        :args:
            :sip:ref:`~PyQt5.QtWebEngineCore.QWebEngineHttpRequest`
        :description: QtWebEngineCore/QWebEngineHttpRequest-__init__-f.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineHttpRequest.__init__
        :args:
            url: :sip:ref:`~PyQt5.QtCore.QUrl` = QUrl()
            method: :sip:ref:`~PyQt5.QtWebEngineCore.QWebEngineHttpRequest.Method` = QWebEngineHttpRequest.Method.Get
        :description: QtWebEngineCore/QWebEngineHttpRequest-__init__-f-1.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineHttpRequest.__eq__
        :args:
            :sip:ref:`~PyQt5.QtWebEngineCore.QWebEngineHttpRequest`
        :returns:
            bool
        :description: QtWebEngineCore/QWebEngineHttpRequest-__eq__-f.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineHttpRequest.hasHeader
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :returns:
            bool
        :description: QtWebEngineCore/QWebEngineHttpRequest-hasHeader-f.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineHttpRequest.header
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :returns:
            :sip:ref:`~PyQt5.QtCore.QByteArray`
        :description: QtWebEngineCore/QWebEngineHttpRequest-header-f.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineHttpRequest.headers
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QByteArray`]
        :description: QtWebEngineCore/QWebEngineHttpRequest-headers-f.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineHttpRequest.method
        :returns:
            :sip:ref:`~PyQt5.QtWebEngineCore.QWebEngineHttpRequest.Method`
        :description: QtWebEngineCore/QWebEngineHttpRequest-method-f.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineHttpRequest.__ne__
        :args:
            :sip:ref:`~PyQt5.QtWebEngineCore.QWebEngineHttpRequest`
        :returns:
            bool
        :description: QtWebEngineCore/QWebEngineHttpRequest-__ne__-f.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineHttpRequest.postData
        :returns:
            :sip:ref:`~PyQt5.QtCore.QByteArray`
        :description: QtWebEngineCore/QWebEngineHttpRequest-postData-f.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineHttpRequest.postRequest
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
            Dict[str, str]
        :returns:
            :sip:ref:`~PyQt5.QtWebEngineCore.QWebEngineHttpRequest`
        :static:
        :description: QtWebEngineCore/QWebEngineHttpRequest-postRequest-f.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineHttpRequest.setHeader
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :description: QtWebEngineCore/QWebEngineHttpRequest-setHeader-f.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineHttpRequest.setMethod
        :args:
            :sip:ref:`~PyQt5.QtWebEngineCore.QWebEngineHttpRequest.Method`
        :description: QtWebEngineCore/QWebEngineHttpRequest-setMethod-f.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineHttpRequest.setPostData
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :description: QtWebEngineCore/QWebEngineHttpRequest-setPostData-f.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineHttpRequest.setUrl
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtWebEngineCore/QWebEngineHttpRequest-setUrl-f.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineHttpRequest.swap
        :args:
            :sip:ref:`~PyQt5.QtWebEngineCore.QWebEngineHttpRequest`
        :description: QtWebEngineCore/QWebEngineHttpRequest-swap-f.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineHttpRequest.unsetHeader
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :description: QtWebEngineCore/QWebEngineHttpRequest-unsetHeader-f.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineHttpRequest.url
        :returns:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtWebEngineCore/QWebEngineHttpRequest-url-f.rst
