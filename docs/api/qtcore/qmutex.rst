:orphan:

.. sip:class:: PyQt5.QtCore.QMutex
    :description: QtCore/QMutex-c.rst

    .. sip:enum:: PyQt5.QtCore.QMutex.RecursionMode
        :description: QtCore/QMutex-RecursionMode-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QMutex.RecursionMode.NonRecursive
            :description: QtCore/QMutex-RecursionMode-NonRecursive-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QMutex.RecursionMode.Recursive
            :description: QtCore/QMutex-RecursionMode-Recursive-v.rst

    .. sip:method:: PyQt5.QtCore.QMutex.__init__
        :args:
            mode: :sip:ref:`~PyQt5.QtCore.QMutex.RecursionMode` = :sip:ref:`~PyQt5.QtCore.QMutex.RecursionMode.NonRecursive`
        :description: QtCore/QMutex-__init__-f.rst

    .. sip:method:: PyQt5.QtCore.QMutex.isRecursive
        :returns:
            bool
        :description: QtCore/QMutex-isRecursive-f.rst

    .. sip:method:: PyQt5.QtCore.QMutex.lock
        :description: QtCore/QMutex-lock-f.rst

    .. sip:method:: PyQt5.QtCore.QMutex.tryLock
        :args:
            timeout: int = 0
        :returns:
            bool
        :description: QtCore/QMutex-tryLock-f.rst

    .. sip:method:: PyQt5.QtCore.QMutex.unlock
        :description: QtCore/QMutex-unlock-f.rst
