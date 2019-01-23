.. sip:method-description::
    :status: todo
    :pysig: 654031b83cf8a95868c6ce1b058d93fe
    :realsig: (QObject*,QEvent*)
    :digest: 50c2f896126e00adb99a42d19d16a522

Sends *event* to *receiver*: *receiver*->event(\ *event*). Returns the value that is returned from the receiver's event handler. Note that this function is called for all events sent to any object in any thread.

For certain types of events (e.g. mouse and key events), the event will be propagated to the receiver's parent and so on up to the top-level object if the receiver is not interested in the event (i.e., it returns ``false``).

There are five different ways that events can be processed; reimplementing this virtual function is just one of them. All five approaches are listed below:

#. Reimplementing :sip:ref:`~PyQt5.QtWidgets.QWidget.paintEvent`, :sip:ref:`~PyQt5.QtWidgets.QWidget.mousePressEvent` and so on. This is the most common, easiest, and least powerful way.

#. Reimplementing this function. This is very powerful, providing complete control; but only one subclass can be active at a time.

#. Installing an event filter on :sip:ref:`~PyQt5.QtCore.QCoreApplication.instance`. Such an event filter is able to process all events for all widgets, so it's just as powerful as reimplementing ; furthermore, it's possible to have more than one application-global event filter. Global event filters even see mouse events for :sip:ref:`~PyQt5.QtWidgets.QWidget.isEnabled`. Note that application event filters are only called for objects that live in the main thread.

#. Reimplementing :sip:ref:`~PyQt5.QtCore.QObject.event` (as :sip:ref:`~PyQt5.QtWidgets.QWidget` does). If you do this you get Tab key presses, and you get to see the events before any widget-specific event filters.

#. Installing an event filter on the object. Such an event filter gets all the events, including Tab and Shift+Tab key press events, as long as they do not change the focus widget.

**Future direction:** This function will not be called for objects that live outside the main thread in Qt 6. Applications that need that functionality should find other solutions for their event inspection needs in the meantime. The change may be extended to the main thread, causing this function to be deprecated.

**Warning:** If you override this function, you must ensure all threads that process events stop doing so before your application object begins destruction. This includes threads started by other libraries that you may be using, but does not apply to Qt's own threads.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QObject.event`.
