.. sip:class-description::
    :status: todo
    :brief: Represents an error received from the D-Bus bus or from remote applications found in the bus
    :digest: 6ecede040481e9fcb750a850d864bc95

The :sip:ref:`~PyQt5.QtDBus.QDBusError` class represents an error received from the D-Bus bus or from remote applications found in the bus.

When dealing with the D-Bus bus service or with remote applications over D-Bus, a number of error conditions can happen. This error conditions are sometimes signalled by a returned error value or by a :sip:ref:`~PyQt5.QtDBus.QDBusError`.

C++ and Java exceptions are a valid analogy for D-Bus errors: instead of returning normally with a return value, remote applications and the bus may decide to throw an error condition. However, the Qt D-Bus implementation does not use the C++ exception-throwing mechanism, so you will receive QDBusErrors in the return reply (see QDBusReply::error()).

:sip:ref:`~PyQt5.QtDBus.QDBusError` objects are used to inspect the error name and message as received from the bus and remote applications. You should not create such objects yourself to signal error conditions when called from D-Bus: instead, use QDBusMessage::createError() and QDBusConnection::send().

.. seealso:: :sip:ref:`~PyQt5.QtDBus.QDBusMessage`, QDBusReply, :sip:ref:`~PyQt5.QtDBus.QDBusConnection.send`.
