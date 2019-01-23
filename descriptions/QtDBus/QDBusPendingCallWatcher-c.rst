.. sip:class-description::
    :status: todo
    :brief: Convenient way for waiting for asynchronous replies
    :digest: 25e3f20dee7efa8669c2258f8cf7da5e

The :sip:ref:`~PyQt5.QtDBus.QDBusPendingCallWatcher` class provides a convenient way for waiting for asynchronous replies.

The :sip:ref:`~PyQt5.QtDBus.QDBusPendingCallWatcher` provides the :sip:ref:`~PyQt5.QtDBus.QDBusPendingCallWatcher.finished` signal that will be emitted when a reply arrives.

It is usually used like the following example:

.. literalinclude:: ../../../snippets/qtbase-src-dbus-doc-snippets-code-src_qdbus_qdbuspendingcall.py
    :lines: 55-59

Note that it is not necessary to keep the original :sip:ref:`~PyQt5.QtDBus.QDBusPendingCall` object around since :sip:ref:`~PyQt5.QtDBus.QDBusPendingCallWatcher` inherits from that class too.

The slot connected to by the above code could be something similar to the following:

.. literalinclude:: ../../../snippets/qtbase-src-dbus-doc-snippets-code-src_qdbus_qdbuspendingcall.py
    :lines: 65-76

Note the use of QDBusPendingReply to validate the argument types in the reply. If the reply did not contain exactly two arguments (one string and one :sip:ref:`~PyQt5.QtCore.QByteArray`), QDBusPendingReply::isError() will return true.

.. seealso:: QDBusPendingReply, :sip:ref:`~PyQt5.QtDBus.QDBusAbstractInterface.asyncCall`.
