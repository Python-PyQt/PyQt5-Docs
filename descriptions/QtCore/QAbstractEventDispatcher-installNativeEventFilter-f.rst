.. sip:method-description::
    :status: todo
    :pysig: 6684e489fe789d40e97ca035d533b2fc
    :realsig: (QAbstractNativeEventFilter*)
    :digest: 2b2257aa1454415f24c8f256e56305d3

Installs an event filter *filterObj* for all native events received by the application.

The event filter *filterObj* receives events via its :sip:ref:`~PyQt5.QtCore.QAbstractNativeEventFilter.nativeEventFilter` function, which is called for all events received by all threads.

The :sip:ref:`~PyQt5.QtCore.QAbstractNativeEventFilter.nativeEventFilter` function should return true if the event should be filtered, (in this case, stopped). It should return false to allow normal Qt processing to continue: the native event can then be translated into a :sip:ref:`~PyQt5.QtCore.QEvent` and handled by the standard Qt :sip:ref:`~PyQt5.QtCore.QEvent` filtering, e.g. :sip:ref:`~PyQt5.QtCore.QObject.installEventFilter`.

If multiple event filters are installed, the filter that was installed last is activated first.

**Note:** The filter function set here receives native messages, that is, MSG or XEvent structs.

For maximum portability, you should always try to use :sip:ref:`~PyQt5.QtCore.QEvent` objects and :sip:ref:`~PyQt5.QtCore.QObject.installEventFilter` whenever possible.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QObject.installEventFilter`.
