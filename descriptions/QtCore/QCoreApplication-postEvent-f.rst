.. sip:method-description::
    :status: todo
    :pysig: 36d4733b278a85301c2c80bcad0c4bec
    :realsig: (QObject*,QEvent*,int)
    :digest: 1002042ad4bd9443ae24ce82c161e63e

Adds the event *event*, with the object *receiver* as the receiver of the event, to an event queue and returns immediately.

The event must be allocated on the heap since the post event queue will take ownership of the event and delete it once it has been posted. It is *not safe* to access the event after it has been posted.

When control returns to the main event loop, all events that are stored in the queue will be sent using the :sip:ref:`~PyQt5.QtCore.QCoreApplication.notify` function.

Events are sorted in descending *priority* order, i.e. events with a high *priority* are queued before events with a lower *priority*. The *priority* can be any integer value, i.e. between INT_MAX and INT_MIN, inclusive; see :sip:ref:`~PyQt5.QtCore.Qt.EventPriority` for more details. Events with equal *priority* will be processed in the order posted.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QCoreApplication.sendEvent`, :sip:ref:`~PyQt5.QtCore.QCoreApplication.notify`, :sip:ref:`~PyQt5.QtCore.QCoreApplication.sendPostedEvents`, :sip:ref:`~PyQt5.QtCore.Qt.EventPriority`.
