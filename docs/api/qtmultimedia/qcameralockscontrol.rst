:orphan:

.. sip:class:: PyQt5.QtMultimedia.QCameraLocksControl
    :inherits: :sip:ref:`~PyQt5.QtMultimedia.QMediaControl`
    :description: QtMultimedia/QCameraLocksControl-c.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraLocksControl.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtMultimedia/QCameraLocksControl-__init__-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraLocksControl.lockStatus
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QCamera.LockType`
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QCamera.LockStatus`
        :description: QtMultimedia/QCameraLocksControl-lockStatus-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraLocksControl.searchAndLock
        :args:
            Union[:sip:ref:`~PyQt5.QtMultimedia.QCamera.LockTypes`, :sip:ref:`~PyQt5.QtMultimedia.QCamera.LockType`]
        :description: QtMultimedia/QCameraLocksControl-searchAndLock-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraLocksControl.supportedLocks
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QCamera.LockTypes`
        :description: QtMultimedia/QCameraLocksControl-supportedLocks-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QCameraLocksControl.unlock
        :args:
            Union[:sip:ref:`~PyQt5.QtMultimedia.QCamera.LockTypes`, :sip:ref:`~PyQt5.QtMultimedia.QCamera.LockType`]
        :description: QtMultimedia/QCameraLocksControl-unlock-f.rst

    .. sip:signal:: PyQt5.QtMultimedia.QCameraLocksControl.lockStatusChanged
        :args:
            :sip:ref:`~PyQt5.QtMultimedia.QCamera.LockType`
            :sip:ref:`~PyQt5.QtMultimedia.QCamera.LockStatus`
            :sip:ref:`~PyQt5.QtMultimedia.QCamera.LockChangeReason`
        :description: QtMultimedia/QCameraLocksControl-lockStatusChanged-s.rst
