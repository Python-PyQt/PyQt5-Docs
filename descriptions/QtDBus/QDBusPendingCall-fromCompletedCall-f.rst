.. sip:method-description::
    :status: todo
    :pysig: d1092b363fcb0303bc9186fc138c8120
    :realsig: (const QDBusMessage&)
    :digest: 5bec2e3d311d7c6ec1157dbcf69d6e1a

Creates a :sip:ref:`~PyQt5.QtDBus.QDBusPendingCall` object based on the message *msg*. The message must be of type :sip:ref:`~PyQt5.QtDBus.QDBusMessage.MessageType.ErrorMessage` or :sip:ref:`~PyQt5.QtDBus.QDBusMessage.MessageType.ReplyMessage` (that is, a message that is typical of a completed call).

This function is useful for code that requires simulating a pending call, but that has already finished.

.. seealso:: :sip:ref:`~PyQt5.QtDBus.QDBusPendingCall.fromError`.
