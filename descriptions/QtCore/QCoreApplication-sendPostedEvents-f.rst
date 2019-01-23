.. sip:method-description::
    :status: todo
    :pysig: e4faee979319e099ea456cafccc8084f
    :realsig: (QObject*,int)
    :digest: 9b6a739eb12ee6f027036a7faa280faf

Immediately dispatches all events which have been previously queued with :sip:ref:`~PyQt5.QtCore.QCoreApplication.postEvent` and which are for the object *receiver* and have the event type *event_type*.

Events from the window system are *not* dispatched by this function, but by :sip:ref:`~PyQt5.QtCore.QCoreApplication.processEvents`.

If *receiver* is null, the events of *event_type* are sent for all objects. If *event_type* is 0, all the events are sent for *receiver*.

**Note:** This method must be called from the thread in which its :sip:ref:`~PyQt5.QtCore.QObject` parameter, *receiver*, lives.

.. seealso:: :sip:ref:`~PyQt5.QtCore.flush`, :sip:ref:`~PyQt5.QtCore.QCoreApplication.postEvent`.
