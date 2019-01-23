:orphan:

.. sip:class:: PyQt5.QtNfc.QNearFieldShareManager
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtNfc/QNearFieldShareManager-c.rst

    .. sip:enum:: PyQt5.QtNfc.QNearFieldShareManager.ShareError
        :description: QtNfc/QNearFieldShareManager-ShareError-e.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldShareManager.ShareError.InvalidShareContentError
            :description: QtNfc/QNearFieldShareManager-ShareError-InvalidShareContentError-v.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldShareManager.ShareError.NoError
            :description: QtNfc/QNearFieldShareManager-ShareError-NoError-v.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldShareManager.ShareError.ShareAlreadyInProgressError
            :description: QtNfc/QNearFieldShareManager-ShareError-ShareAlreadyInProgressError-v.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldShareManager.ShareError.ShareCanceledError
            :description: QtNfc/QNearFieldShareManager-ShareError-ShareCanceledError-v.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldShareManager.ShareError.ShareInterruptedError
            :description: QtNfc/QNearFieldShareManager-ShareError-ShareInterruptedError-v.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldShareManager.ShareError.SharePermissionDeniedError
            :description: QtNfc/QNearFieldShareManager-ShareError-SharePermissionDeniedError-v.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldShareManager.ShareError.ShareRejectedError
            :description: QtNfc/QNearFieldShareManager-ShareError-ShareRejectedError-v.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldShareManager.ShareError.UnknownError
            :description: QtNfc/QNearFieldShareManager-ShareError-UnknownError-v.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldShareManager.ShareError.UnsupportedShareModeError
            :description: QtNfc/QNearFieldShareManager-ShareError-UnsupportedShareModeError-v.rst

    .. sip:enum:: PyQt5.QtNfc.QNearFieldShareManager.ShareMode
        :description: QtNfc/QNearFieldShareManager-ShareMode-e.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldShareManager.ShareMode.FileShare
            :description: QtNfc/QNearFieldShareManager-ShareMode-FileShare-v.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldShareManager.ShareMode.NdefShare
            :description: QtNfc/QNearFieldShareManager-ShareMode-NdefShare-v.rst

        .. sip:enum-member:: PyQt5.QtNfc.QNearFieldShareManager.ShareMode.NoShare
            :description: QtNfc/QNearFieldShareManager-ShareMode-NoShare-v.rst

    .. sip:method:: PyQt5.QtNfc.QNearFieldShareManager.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtNfc/QNearFieldShareManager-__init__-f.rst

    .. sip:method:: PyQt5.QtNfc.QNearFieldShareManager.setShareModes
        :args:
            Union[:sip:ref:`~PyQt5.QtNfc.QNearFieldShareManager.ShareModes`, :sip:ref:`~PyQt5.QtNfc.QNearFieldShareManager.ShareMode`]
        :description: QtNfc/QNearFieldShareManager-setShareModes-f.rst

    .. sip:method:: PyQt5.QtNfc.QNearFieldShareManager.shareError
        :returns:
            :sip:ref:`~PyQt5.QtNfc.QNearFieldShareManager.ShareError`
        :description: QtNfc/QNearFieldShareManager-shareError-f.rst

    .. sip:method:: PyQt5.QtNfc.QNearFieldShareManager.shareModes
        :returns:
            :sip:ref:`~PyQt5.QtNfc.QNearFieldShareManager.ShareModes`
        :description: QtNfc/QNearFieldShareManager-shareModes-f.rst

    .. sip:method:: PyQt5.QtNfc.QNearFieldShareManager.supportedShareModes
        :returns:
            :sip:ref:`~PyQt5.QtNfc.QNearFieldShareManager.ShareModes`
        :static:
        :description: QtNfc/QNearFieldShareManager-supportedShareModes-f.rst

    .. sip:signal:: PyQt5.QtNfc.QNearFieldShareManager.error
        :args:
            :sip:ref:`~PyQt5.QtNfc.QNearFieldShareManager.ShareError`
        :description: QtNfc/QNearFieldShareManager-error-s.rst

    .. sip:signal:: PyQt5.QtNfc.QNearFieldShareManager.shareModesChanged
        :args:
            Union[:sip:ref:`~PyQt5.QtNfc.QNearFieldShareManager.ShareModes`, :sip:ref:`~PyQt5.QtNfc.QNearFieldShareManager.ShareMode`]
        :description: QtNfc/QNearFieldShareManager-shareModesChanged-s.rst

    .. sip:signal:: PyQt5.QtNfc.QNearFieldShareManager.targetDetected
        :args:
            :sip:ref:`~PyQt5.QtNfc.QNearFieldShareTarget`
        :description: QtNfc/QNearFieldShareManager-targetDetected-s.rst
