:orphan:

.. sip:class:: PyQt5.QtPurchasing.QInAppTransaction
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtPurchasing/QInAppTransaction-c.rst

    .. sip:enum:: PyQt5.QtPurchasing.QInAppTransaction.FailureReason
        :description: QtPurchasing/QInAppTransaction-FailureReason-e.rst

        .. sip:enum-member:: PyQt5.QtPurchasing.QInAppTransaction.FailureReason.CanceledByUser
            :description: QtPurchasing/QInAppTransaction-FailureReason-CanceledByUser-v.rst

        .. sip:enum-member:: PyQt5.QtPurchasing.QInAppTransaction.FailureReason.ErrorOccurred
            :description: QtPurchasing/QInAppTransaction-FailureReason-ErrorOccurred-v.rst

        .. sip:enum-member:: PyQt5.QtPurchasing.QInAppTransaction.FailureReason.NoFailure
            :description: QtPurchasing/QInAppTransaction-FailureReason-NoFailure-v.rst

    .. sip:enum:: PyQt5.QtPurchasing.QInAppTransaction.TransactionStatus
        :description: QtPurchasing/QInAppTransaction-TransactionStatus-e.rst

        .. sip:enum-member:: PyQt5.QtPurchasing.QInAppTransaction.TransactionStatus.PurchaseApproved
            :description: QtPurchasing/QInAppTransaction-TransactionStatus-PurchaseApproved-v.rst

        .. sip:enum-member:: PyQt5.QtPurchasing.QInAppTransaction.TransactionStatus.PurchaseFailed
            :description: QtPurchasing/QInAppTransaction-TransactionStatus-PurchaseFailed-v.rst

        .. sip:enum-member:: PyQt5.QtPurchasing.QInAppTransaction.TransactionStatus.PurchaseRestored
            :description: QtPurchasing/QInAppTransaction-TransactionStatus-PurchaseRestored-v.rst

        .. sip:enum-member:: PyQt5.QtPurchasing.QInAppTransaction.TransactionStatus.Unknown
            :description: QtPurchasing/QInAppTransaction-TransactionStatus-Unknown-v.rst

    .. sip:method:: PyQt5.QtPurchasing.QInAppTransaction.errorString
        :returns:
            str
        :description: QtPurchasing/QInAppTransaction-errorString-f.rst

    .. sip:method:: PyQt5.QtPurchasing.QInAppTransaction.failureReason
        :returns:
            :sip:ref:`~PyQt5.QtPurchasing.QInAppTransaction.FailureReason`
        :description: QtPurchasing/QInAppTransaction-failureReason-f.rst

    .. sip:method:: PyQt5.QtPurchasing.QInAppTransaction.finalize
        :description: QtPurchasing/QInAppTransaction-finalize-f.rst

    .. sip:method:: PyQt5.QtPurchasing.QInAppTransaction.orderId
        :returns:
            str
        :description: QtPurchasing/QInAppTransaction-orderId-f.rst

    .. sip:method:: PyQt5.QtPurchasing.QInAppTransaction.platformProperty
        :args:
            str
        :returns:
            str
        :description: QtPurchasing/QInAppTransaction-platformProperty-f.rst

    .. sip:method:: PyQt5.QtPurchasing.QInAppTransaction.product
        :returns:
            :sip:ref:`~PyQt5.QtPurchasing.QInAppProduct`
        :description: QtPurchasing/QInAppTransaction-product-f.rst

    .. sip:method:: PyQt5.QtPurchasing.QInAppTransaction.status
        :returns:
            :sip:ref:`~PyQt5.QtPurchasing.QInAppTransaction.TransactionStatus`
        :description: QtPurchasing/QInAppTransaction-status-f.rst

    .. sip:method:: PyQt5.QtPurchasing.QInAppTransaction.timestamp
        :returns:
            :sip:ref:`~PyQt5.QtCore.QDateTime`
        :description: QtPurchasing/QInAppTransaction-timestamp-f.rst
