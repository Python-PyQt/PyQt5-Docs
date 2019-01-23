:orphan:

.. sip:class:: PyQt5.QtCore.QReadWriteLock
    :description: QtCore/QReadWriteLock-c.rst

    .. sip:enum:: PyQt5.QtCore.QReadWriteLock.RecursionMode
        :description: QtCore/QReadWriteLock-RecursionMode-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QReadWriteLock.RecursionMode.NonRecursive
            :description: QtCore/QReadWriteLock-RecursionMode-NonRecursive-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QReadWriteLock.RecursionMode.Recursive
            :description: QtCore/QReadWriteLock-RecursionMode-Recursive-v.rst

    .. sip:method:: PyQt5.QtCore.QReadWriteLock.__init__
        :args:
            recursionMode: :sip:ref:`~PyQt5.QtCore.QReadWriteLock.RecursionMode` = :sip:ref:`~PyQt5.QtCore.QReadWriteLock.RecursionMode.NonRecursive`
        :description: QtCore/QReadWriteLock-__init__-f.rst

    .. sip:method:: PyQt5.QtCore.QReadWriteLock.lockForRead
        :description: QtCore/QReadWriteLock-lockForRead-f.rst

    .. sip:method:: PyQt5.QtCore.QReadWriteLock.lockForWrite
        :description: QtCore/QReadWriteLock-lockForWrite-f.rst

    .. sip:method:: PyQt5.QtCore.QReadWriteLock.tryLockForRead
        :returns:
            bool
        :description: QtCore/QReadWriteLock-tryLockForRead-f.rst

    .. sip:method:: PyQt5.QtCore.QReadWriteLock.tryLockForRead
        :args:
            int
        :returns:
            bool
        :description: QtCore/QReadWriteLock-tryLockForRead-f-1.rst

    .. sip:method:: PyQt5.QtCore.QReadWriteLock.tryLockForWrite
        :returns:
            bool
        :description: QtCore/QReadWriteLock-tryLockForWrite-f.rst

    .. sip:method:: PyQt5.QtCore.QReadWriteLock.tryLockForWrite
        :args:
            int
        :returns:
            bool
        :description: QtCore/QReadWriteLock-tryLockForWrite-f-1.rst

    .. sip:method:: PyQt5.QtCore.QReadWriteLock.unlock
        :description: QtCore/QReadWriteLock-unlock-f.rst
