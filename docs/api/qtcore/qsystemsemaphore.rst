:orphan:

.. sip:class:: PyQt5.QtCore.QSystemSemaphore
    :description: QtCore/QSystemSemaphore-c.rst

    .. sip:enum:: PyQt5.QtCore.QSystemSemaphore.AccessMode
        :description: QtCore/QSystemSemaphore-AccessMode-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QSystemSemaphore.AccessMode.Create
            :description: QtCore/QSystemSemaphore-AccessMode-Create-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QSystemSemaphore.AccessMode.Open
            :description: QtCore/QSystemSemaphore-AccessMode-Open-v.rst

    .. sip:enum:: PyQt5.QtCore.QSystemSemaphore.SystemSemaphoreError
        :description: QtCore/QSystemSemaphore-SystemSemaphoreError-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QSystemSemaphore.SystemSemaphoreError.AlreadyExists
            :description: QtCore/QSystemSemaphore-SystemSemaphoreError-AlreadyExists-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QSystemSemaphore.SystemSemaphoreError.KeyError
            :description: QtCore/QSystemSemaphore-SystemSemaphoreError-KeyError-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QSystemSemaphore.SystemSemaphoreError.NoError
            :description: QtCore/QSystemSemaphore-SystemSemaphoreError-NoError-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QSystemSemaphore.SystemSemaphoreError.NotFound
            :description: QtCore/QSystemSemaphore-SystemSemaphoreError-NotFound-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QSystemSemaphore.SystemSemaphoreError.OutOfResources
            :description: QtCore/QSystemSemaphore-SystemSemaphoreError-OutOfResources-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QSystemSemaphore.SystemSemaphoreError.PermissionDenied
            :description: QtCore/QSystemSemaphore-SystemSemaphoreError-PermissionDenied-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QSystemSemaphore.SystemSemaphoreError.UnknownError
            :description: QtCore/QSystemSemaphore-SystemSemaphoreError-UnknownError-v.rst

    .. sip:method:: PyQt5.QtCore.QSystemSemaphore.__init__
        :args:
            str
            initialValue: int = 0
            mode: :sip:ref:`~PyQt5.QtCore.QSystemSemaphore.AccessMode` = :sip:ref:`~PyQt5.QtCore.QSystemSemaphore.AccessMode.Open`
        :description: QtCore/QSystemSemaphore-__init__-f.rst

    .. sip:method:: PyQt5.QtCore.QSystemSemaphore.acquire
        :returns:
            bool
        :description: QtCore/QSystemSemaphore-acquire-f.rst

    .. sip:method:: PyQt5.QtCore.QSystemSemaphore.error
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSystemSemaphore.SystemSemaphoreError`
        :description: QtCore/QSystemSemaphore-error-f.rst

    .. sip:method:: PyQt5.QtCore.QSystemSemaphore.errorString
        :returns:
            str
        :description: QtCore/QSystemSemaphore-errorString-f.rst

    .. sip:method:: PyQt5.QtCore.QSystemSemaphore.key
        :returns:
            str
        :description: QtCore/QSystemSemaphore-key-f.rst

    .. sip:method:: PyQt5.QtCore.QSystemSemaphore.release
        :args:
            n: int = 1
        :returns:
            bool
        :description: QtCore/QSystemSemaphore-release-f.rst

    .. sip:method:: PyQt5.QtCore.QSystemSemaphore.setKey
        :args:
            str
            initialValue: int = 0
            mode: :sip:ref:`~PyQt5.QtCore.QSystemSemaphore.AccessMode` = :sip:ref:`~PyQt5.QtCore.QSystemSemaphore.AccessMode.Open`
        :description: QtCore/QSystemSemaphore-setKey-f.rst
