:orphan:

.. sip:class:: PyQt5.QtPurchasing.QInAppStore
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtPurchasing/QInAppStore-c.rst

    .. sip:method:: PyQt5.QtPurchasing.QInAppStore.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtPurchasing/QInAppStore-__init__-f.rst

    .. sip:method:: PyQt5.QtPurchasing.QInAppStore.registeredProduct
        :args:
            str
        :returns:
            :sip:ref:`~PyQt5.QtPurchasing.QInAppProduct`
        :description: QtPurchasing/QInAppStore-registeredProduct-f.rst

    .. sip:method:: PyQt5.QtPurchasing.QInAppStore.registerProduct
        :args:
            :sip:ref:`~PyQt5.QtPurchasing.QInAppProduct.ProductType`
            str
        :description: QtPurchasing/QInAppStore-registerProduct-f.rst

    .. sip:method:: PyQt5.QtPurchasing.QInAppStore.restorePurchases
        :description: QtPurchasing/QInAppStore-restorePurchases-f.rst

    .. sip:method:: PyQt5.QtPurchasing.QInAppStore.setPlatformProperty
        :args:
            str
            str
        :description: QtPurchasing/QInAppStore-setPlatformProperty-f.rst

    .. sip:signal:: PyQt5.QtPurchasing.QInAppStore.productRegistered
        :args:
            :sip:ref:`~PyQt5.QtPurchasing.QInAppProduct`
        :description: QtPurchasing/QInAppStore-productRegistered-s.rst

    .. sip:signal:: PyQt5.QtPurchasing.QInAppStore.productUnknown
        :args:
            :sip:ref:`~PyQt5.QtPurchasing.QInAppProduct.ProductType`
            str
        :description: QtPurchasing/QInAppStore-productUnknown-s.rst

    .. sip:signal:: PyQt5.QtPurchasing.QInAppStore.transactionReady
        :args:
            :sip:ref:`~PyQt5.QtPurchasing.QInAppTransaction`
        :description: QtPurchasing/QInAppStore-transactionReady-s.rst
