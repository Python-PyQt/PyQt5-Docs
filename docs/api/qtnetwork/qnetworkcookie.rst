:orphan:

.. sip:class:: PyQt5.QtNetwork.QNetworkCookie
    :description: QtNetwork/QNetworkCookie-c.rst

    .. sip:enum:: PyQt5.QtNetwork.QNetworkCookie.RawForm
        :description: QtNetwork/QNetworkCookie-RawForm-e.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkCookie.RawForm.Full
            :description: QtNetwork/QNetworkCookie-RawForm-Full-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QNetworkCookie.RawForm.NameAndValueOnly
            :description: QtNetwork/QNetworkCookie-RawForm-NameAndValueOnly-v.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkCookie.__init__
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkCookie`
        :description: QtNetwork/QNetworkCookie-__init__-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkCookie.__init__
        :args:
            name: Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray] = QByteArray()
            value: Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray] = QByteArray()
        :description: QtNetwork/QNetworkCookie-__init__-f-1.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkCookie.domain
        :returns:
            str
        :description: QtNetwork/QNetworkCookie-domain-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkCookie.__eq__
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkCookie`
        :returns:
            bool
        :description: QtNetwork/QNetworkCookie-__eq__-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkCookie.expirationDate
        :returns:
            :sip:ref:`~PyQt5.QtCore.QDateTime`
        :description: QtNetwork/QNetworkCookie-expirationDate-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkCookie.hasSameIdentifier
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkCookie`
        :returns:
            bool
        :description: QtNetwork/QNetworkCookie-hasSameIdentifier-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkCookie.isHttpOnly
        :returns:
            bool
        :description: QtNetwork/QNetworkCookie-isHttpOnly-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkCookie.isSecure
        :returns:
            bool
        :description: QtNetwork/QNetworkCookie-isSecure-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkCookie.isSessionCookie
        :returns:
            bool
        :description: QtNetwork/QNetworkCookie-isSessionCookie-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkCookie.name
        :returns:
            :sip:ref:`~PyQt5.QtCore.QByteArray`
        :description: QtNetwork/QNetworkCookie-name-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkCookie.__ne__
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkCookie`
        :returns:
            bool
        :description: QtNetwork/QNetworkCookie-__ne__-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkCookie.normalize
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtNetwork/QNetworkCookie-normalize-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkCookie.parseCookies
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :returns:
            List[:sip:ref:`~PyQt5.QtNetwork.QNetworkCookie`]
        :static:
        :description: QtNetwork/QNetworkCookie-parseCookies-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkCookie.path
        :returns:
            str
        :description: QtNetwork/QNetworkCookie-path-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkCookie.setDomain
        :args:
            str
        :description: QtNetwork/QNetworkCookie-setDomain-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkCookie.setExpirationDate
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QDateTime`, datetime.datetime]
        :description: QtNetwork/QNetworkCookie-setExpirationDate-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkCookie.setHttpOnly
        :args:
            bool
        :description: QtNetwork/QNetworkCookie-setHttpOnly-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkCookie.setName
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :description: QtNetwork/QNetworkCookie-setName-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkCookie.setPath
        :args:
            str
        :description: QtNetwork/QNetworkCookie-setPath-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkCookie.setSecure
        :args:
            bool
        :description: QtNetwork/QNetworkCookie-setSecure-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkCookie.setValue
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :description: QtNetwork/QNetworkCookie-setValue-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkCookie.swap
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QNetworkCookie`
        :description: QtNetwork/QNetworkCookie-swap-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkCookie.toRawForm
        :args:
            form: :sip:ref:`~PyQt5.QtNetwork.QNetworkCookie.RawForm` = :sip:ref:`~PyQt5.QtNetwork.QNetworkCookie.RawForm.Full`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QByteArray`
        :description: QtNetwork/QNetworkCookie-toRawForm-f.rst

    .. sip:method:: PyQt5.QtNetwork.QNetworkCookie.value
        :returns:
            :sip:ref:`~PyQt5.QtCore.QByteArray`
        :description: QtNetwork/QNetworkCookie-value-f.rst
