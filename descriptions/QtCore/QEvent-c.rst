.. sip:class-description::
    :status: todo
    :brief: The base class of all event classes. Event objects contain event parameters
    :digest: 35c9ab2af884a703c4a9fdc9351896f2

The :sip:ref:`~PyQt5.QtCore.QEvent` class is the base class of all event classes. Event objects contain event parameters.

Qt's main event loop (\ :sip:ref:`~PyQt5.QtCore.QCoreApplication.exec`) fetches native window system events from the event queue, translates them into QEvents, and sends the translated events to :sip:ref:`~PyQt5.QtCore.QObject`\ s.

In general, events come from the underlying window system (\ :sip:ref:`~PyQt5.QtCore.QEvent.spontaneous` returns ``true``), but it is also possible to manually send events using :sip:ref:`~PyQt5.QtCore.QCoreApplication.sendEvent` and :sip:ref:`~PyQt5.QtCore.QCoreApplication.postEvent` (\ :sip:ref:`~PyQt5.QtCore.QEvent.spontaneous` returns ``false``).

:sip:ref:`~PyQt5.QtCore.QObject` receive events by having their :sip:ref:`~PyQt5.QtCore.QObject.event` function called. The function can be reimplemented in subclasses to customize event handling and add additional event types; :sip:ref:`~PyQt5.QtWidgets.QWidget.event` is a notable example. By default, events are dispatched to event handlers like :sip:ref:`~PyQt5.QtCore.QObject.timerEvent` and :sip:ref:`~PyQt5.QtWidgets.QWidget.mouseMoveEvent`. :sip:ref:`~PyQt5.QtCore.QObject.installEventFilter` allows an object to intercept events destined for another object.

The basic :sip:ref:`~PyQt5.QtCore.QEvent` contains only an event type parameter and an "accept" flag. The accept flag set with :sip:ref:`~PyQt5.QtCore.QEvent.accept`, and cleared with :sip:ref:`~PyQt5.QtCore.QEvent.ignore`. It is set by default, but don't rely on this as subclasses may choose to clear it in their constructor.

Subclasses of :sip:ref:`~PyQt5.QtCore.QEvent` contain additional parameters that describe the particular event.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QObject.event`, :sip:ref:`~PyQt5.QtCore.QObject.installEventFilter`, :sip:ref:`~PyQt5.QtCore.QCoreApplication.sendEvent`, :sip:ref:`~PyQt5.QtCore.QCoreApplication.postEvent`, :sip:ref:`~PyQt5.QtCore.QCoreApplication.processEvents`.
