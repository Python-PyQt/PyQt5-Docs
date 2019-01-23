:orphan:

.. sip:class:: PyQt5.QtDBus.QDBusAbstractInterface
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtDBus/QDBusAbstractInterface-c.rst

    .. sip:method:: PyQt5.QtDBus.QDBusAbstractInterface.__init__
        :args:
            str
            str
            str
            :sip:ref:`~PyQt5.QtDBus.QDBusConnection`
            :sip:ref:`~PyQt5.QtCore.QObject`
        :description: QtDBus/QDBusAbstractInterface-__init__-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusAbstractInterface.asyncCall
        :args:
            str
            arg1: Any = None
            arg2: Any = None
            arg3: Any = None
            arg4: Any = None
            arg5: Any = None
            arg6: Any = None
            arg7: Any = None
            arg8: Any = None
        :returns:
            :sip:ref:`~PyQt5.QtDBus.QDBusPendingCall`
        :description: QtDBus/QDBusAbstractInterface-asyncCall-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusAbstractInterface.asyncCallWithArgumentList
        :args:
            str
            Iterable[Any]
        :returns:
            :sip:ref:`~PyQt5.QtDBus.QDBusPendingCall`
        :description: QtDBus/QDBusAbstractInterface-asyncCallWithArgumentList-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusAbstractInterface.call
        :args:
            str
            arg1: Any = None
            arg2: Any = None
            arg3: Any = None
            arg4: Any = None
            arg5: Any = None
            arg6: Any = None
            arg7: Any = None
            arg8: Any = None
        :returns:
            :sip:ref:`~PyQt5.QtDBus.QDBusMessage`
        :description: QtDBus/QDBusAbstractInterface-call-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusAbstractInterface.call
        :args:
            :sip:ref:`~PyQt5.QtDBus.QDBus.CallMode`
            str
            arg1: Any = None
            arg2: Any = None
            arg3: Any = None
            arg4: Any = None
            arg5: Any = None
            arg6: Any = None
            arg7: Any = None
            arg8: Any = None
        :returns:
            :sip:ref:`~PyQt5.QtDBus.QDBusMessage`
        :description: QtDBus/QDBusAbstractInterface-call-f-1.rst

    .. sip:method:: PyQt5.QtDBus.QDBusAbstractInterface.callWithArgumentList
        :args:
            :sip:ref:`~PyQt5.QtDBus.QDBus.CallMode`
            str
            Iterable[Any]
        :returns:
            :sip:ref:`~PyQt5.QtDBus.QDBusMessage`
        :description: QtDBus/QDBusAbstractInterface-callWithArgumentList-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusAbstractInterface.callWithCallback
        :args:
            str
            Iterable[Any]
            PYQT_SLOT
        :returns:
            bool
        :description: QtDBus/QDBusAbstractInterface-callWithCallback-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusAbstractInterface.callWithCallback
        :args:
            str
            Iterable[Any]
            PYQT_SLOT
            PYQT_SLOT
        :returns:
            bool
        :description: QtDBus/QDBusAbstractInterface-callWithCallback-f-1.rst

    .. sip:method:: PyQt5.QtDBus.QDBusAbstractInterface.connection
        :returns:
            :sip:ref:`~PyQt5.QtDBus.QDBusConnection`
        :description: QtDBus/QDBusAbstractInterface-connection-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusAbstractInterface.connectNotify
        :args:
            :sip:ref:`~PyQt5.QtCore.QMetaMethod`
        :description: QtDBus/QDBusAbstractInterface-connectNotify-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusAbstractInterface.disconnectNotify
        :args:
            :sip:ref:`~PyQt5.QtCore.QMetaMethod`
        :description: QtDBus/QDBusAbstractInterface-disconnectNotify-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusAbstractInterface.interface
        :returns:
            str
        :description: QtDBus/QDBusAbstractInterface-interface-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusAbstractInterface.isValid
        :returns:
            bool
        :description: QtDBus/QDBusAbstractInterface-isValid-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusAbstractInterface.lastError
        :returns:
            :sip:ref:`~PyQt5.QtDBus.QDBusError`
        :description: QtDBus/QDBusAbstractInterface-lastError-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusAbstractInterface.path
        :returns:
            str
        :description: QtDBus/QDBusAbstractInterface-path-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusAbstractInterface.service
        :returns:
            str
        :description: QtDBus/QDBusAbstractInterface-service-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusAbstractInterface.setTimeout
        :args:
            int
        :description: QtDBus/QDBusAbstractInterface-setTimeout-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusAbstractInterface.timeout
        :returns:
            int
        :description: QtDBus/QDBusAbstractInterface-timeout-f.rst
