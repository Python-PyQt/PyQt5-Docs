.. sip:enum-description::
    :status: todo
    :digest: 4362eb1e7e70e42cf07ab583d84f272f

This enum is used with :sip:ref:`~PyQt5.QtCore.QIODevice.open` to describe the mode in which a device is opened. It is also returned by :sip:ref:`~PyQt5.QtCore.QIODevice.openMode`.

Certain flags, such as ``Unbuffered`` and ``Truncate``, are meaningless when used with some subclasses. Some of these restrictions are implied by the type of device that is represented by a subclass. In other cases, the restriction may be due to the implementation, or may be imposed by the underlying platform; for example, :sip:ref:`~PyQt5.QtNetwork.QTcpSocket` does not support ``Unbuffered`` mode, and limitations in the native API prevent :sip:ref:`~PyQt5.QtCore.QFile` from supporting ``Unbuffered`` on Windows.
