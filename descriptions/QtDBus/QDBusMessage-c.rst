.. sip:class-description::
    :status: todo
    :brief: Represents one message sent or received over the D-Bus bus
    :digest: d43035167699c40a6da97f83c6978169

The :sip:ref:`~PyQt5.QtDBus.QDBusMessage` class represents one message sent or received over the D-Bus bus.

This object can represent any of the four different types of messages (\ :sip:ref:`~PyQt5.QtDBus.QDBusMessage.MessageType.MessageType`) that can occur on the bus:

* Method calls

* Method return values

* Signal emissions

* Error codes

Objects of this type are created with the static :sip:ref:`~PyQt5.QtDBus.QDBusMessage.createError`, :sip:ref:`~PyQt5.QtDBus.QDBusMessage.createMethodCall` and createSignal() functions. Use the QDBusConnection::send() function to send the messages.
