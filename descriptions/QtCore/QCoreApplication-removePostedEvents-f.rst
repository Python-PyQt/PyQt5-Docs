.. sip:method-description::
    :status: todo
    :pysig: bfe6acb2b0fcd9275378e6ec9a05116d
    :realsig: (QObject*,int)
    :digest: a3a1352e4ac17306ab83de3adb40d745

Removes all events of the given *eventType* that were posted using :sip:ref:`~PyQt5.QtCore.QCoreApplication.postEvent` for *receiver*.

The events are *not* dispatched, instead they are removed from the queue. You should never need to call this function. If you do call it, be aware that killing events may cause *receiver* to break one or more invariants.

If *receiver* is null, the events of *eventType* are removed for all objects. If *eventType* is 0, all the events are removed for *receiver*. You should never call this function with *eventType* of 0.
