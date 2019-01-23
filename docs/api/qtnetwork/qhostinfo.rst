:orphan:

.. sip:class:: PyQt5.QtNetwork.QHostInfo
    :description: QtNetwork/QHostInfo-c.rst

    .. sip:enum:: PyQt5.QtNetwork.QHostInfo.HostInfoError
        :description: QtNetwork/QHostInfo-HostInfoError-e.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QHostInfo.HostInfoError.HostNotFound
            :description: QtNetwork/QHostInfo-HostInfoError-HostNotFound-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QHostInfo.HostInfoError.NoError
            :description: QtNetwork/QHostInfo-HostInfoError-NoError-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QHostInfo.HostInfoError.UnknownError
            :description: QtNetwork/QHostInfo-HostInfoError-UnknownError-v.rst

    .. sip:method:: PyQt5.QtNetwork.QHostInfo.__init__
        :args:
            id: int = -1
        :description: QtNetwork/QHostInfo-__init__-f.rst

    .. sip:method:: PyQt5.QtNetwork.QHostInfo.__init__
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QHostInfo`
        :description: QtNetwork/QHostInfo-__init__-f-1.rst

    .. sip:method:: PyQt5.QtNetwork.QHostInfo.abortHostLookup
        :args:
            int
        :static:
        :description: QtNetwork/QHostInfo-abortHostLookup-f.rst

    .. sip:method:: PyQt5.QtNetwork.QHostInfo.addresses
        :returns:
            List[:sip:ref:`~PyQt5.QtNetwork.QHostAddress`]
        :description: QtNetwork/QHostInfo-addresses-f.rst

    .. sip:method:: PyQt5.QtNetwork.QHostInfo.error
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QHostInfo.HostInfoError`
        :description: QtNetwork/QHostInfo-error-f.rst

    .. sip:method:: PyQt5.QtNetwork.QHostInfo.errorString
        :returns:
            str
        :description: QtNetwork/QHostInfo-errorString-f.rst

    .. sip:method:: PyQt5.QtNetwork.QHostInfo.fromName
        :args:
            str
        :returns:
            :sip:ref:`~PyQt5.QtNetwork.QHostInfo`
        :static:
        :description: QtNetwork/QHostInfo-fromName-f.rst

    .. sip:method:: PyQt5.QtNetwork.QHostInfo.hostName
        :returns:
            str
        :description: QtNetwork/QHostInfo-hostName-f.rst

    .. sip:method:: PyQt5.QtNetwork.QHostInfo.localDomainName
        :returns:
            str
        :static:
        :description: QtNetwork/QHostInfo-localDomainName-f.rst

    .. sip:method:: PyQt5.QtNetwork.QHostInfo.localHostName
        :returns:
            str
        :static:
        :description: QtNetwork/QHostInfo-localHostName-f.rst

    .. sip:method:: PyQt5.QtNetwork.QHostInfo.lookupHost
        :args:
            str
            PYQT_SLOT
        :returns:
            int
        :static:
        :description: QtNetwork/QHostInfo-lookupHost-f.rst

    .. sip:method:: PyQt5.QtNetwork.QHostInfo.lookupId
        :returns:
            int
        :description: QtNetwork/QHostInfo-lookupId-f.rst

    .. sip:method:: PyQt5.QtNetwork.QHostInfo.setAddresses
        :args:
            Iterable[Union[:sip:ref:`~PyQt5.QtNetwork.QHostAddress`, :sip:ref:`~PyQt5.QtNetwork.QHostAddress.SpecialAddress`]]
        :description: QtNetwork/QHostInfo-setAddresses-f.rst

    .. sip:method:: PyQt5.QtNetwork.QHostInfo.setError
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QHostInfo.HostInfoError`
        :description: QtNetwork/QHostInfo-setError-f.rst

    .. sip:method:: PyQt5.QtNetwork.QHostInfo.setErrorString
        :args:
            str
        :description: QtNetwork/QHostInfo-setErrorString-f.rst

    .. sip:method:: PyQt5.QtNetwork.QHostInfo.setHostName
        :args:
            str
        :description: QtNetwork/QHostInfo-setHostName-f.rst

    .. sip:method:: PyQt5.QtNetwork.QHostInfo.setLookupId
        :args:
            int
        :description: QtNetwork/QHostInfo-setLookupId-f.rst

    .. sip:method:: PyQt5.QtNetwork.QHostInfo.swap
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QHostInfo`
        :description: QtNetwork/QHostInfo-swap-f.rst
