.. sip:class-description::
    :status: todo
    :brief: Allows the user to watch for a bus service change
    :digest: 06138a62e9bda2b4d8da014a745c8edd

The :sip:ref:`~PyQt5.QtDBus.QDBusServiceWatcher` class allows the user to watch for a bus service change.

A :sip:ref:`~PyQt5.QtDBus.QDBusServiceWatcher` object can be used to notify the application about an ownership change of a service name on the bus. It has three watch modes:

* Watching for service registration only.

* Watching for service unregistration only.

* Watching for any kind of service ownership change (the default mode).

Besides being created or deleted, services may change owners without a unregister/register operation happening. So the :sip:ref:`~PyQt5.QtDBus.QDBusServiceWatcher.serviceRegistered` and :sip:ref:`~PyQt5.QtDBus.QDBusServiceWatcher.serviceUnregistered` signals may not be emitted if that happens.

This class is more efficient than using the :sip:ref:`~PyQt5.QtDBus.QDBusConnectionInterface.serviceOwnerChanged` signal because it allows one to receive only the signals for which the class is interested in.

.. seealso:: :sip:ref:`~PyQt5.QtDBus.QDBusConnection`.
