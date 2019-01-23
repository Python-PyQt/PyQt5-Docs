.. sip:class-description::
    :status: todo
    :brief: Interface for communicating with a target device
    :digest: 5c7b8498630edb9659284f29f7a72c32

The :sip:ref:`~PyQt5.QtNfc.QNearFieldTarget` class provides an interface for communicating with a target device.

:sip:ref:`~PyQt5.QtNfc.QNearFieldTarget` provides a generic interface for communicating with an NFC target device. Both NFC Forum devices and NFC Forum Tag targets are supported by this class. All target specific classes subclass this class.

The `type() <https://doc.qt.io/qt-5/qml-geoshape.html#type>`_ function can be used to get the type of the target device. The uid() function returns the unique identifier of the target. The AccessMethods flags returns from the accessMethods() function can be tested to determine which access methods are supported by the target.

If the target supports NdefAccess, hasNdefMessage() can be called to test if the target has a stored NDEF message, readNdefMessages() and writeNdefMessages() functions can be used to get and set the NDEF message.

If the target supports TagTypeSpecificAccess, sendCommand() can be used to send a single proprietary command to the target and retrieve the response. sendCommands() can be used to send multiple proprietary commands to the target and retrieve all of the responses.

If the target supports LlcpAccess, the QLlcpSocket class can be used to connected to a service provided by the target.
