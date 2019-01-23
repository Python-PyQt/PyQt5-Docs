.. sip:method-description::
    :status: todo
    :pysig: f4aa8bf3b93f765a5fd83d981111d3fe
    :realsig: (const QByteArray&,void*,long*)
    :digest: 7be98863f95f2bca2b9444a3a9608c2c

Sends *message* through the event filters that were set by :sip:ref:`~PyQt5.QtCore.QAbstractEventDispatcher.installNativeEventFilter`. This function returns ``true`` as soon as an event filter returns ``true``, and false otherwise to indicate that the processing of the event should continue.

Subclasses of :sip:ref:`~PyQt5.QtCore.QAbstractEventDispatcher` *must* call this function for *all* messages received from the system to ensure compatibility with any extensions that may be used in the application. The type of event *eventType* is specific to the platform plugin chosen at run-time, and can be used to cast message to the right type. The *result* pointer is only used on Windows, and corresponds to the LRESULT pointer.

Note that the type of *message* is platform dependent. See :sip:ref:`~PyQt5.QtCore.QAbstractNativeEventFilter` for details.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QAbstractEventDispatcher.installNativeEventFilter`, :sip:ref:`~PyQt5.QtCore.QAbstractNativeEventFilter.nativeEventFilter`.
