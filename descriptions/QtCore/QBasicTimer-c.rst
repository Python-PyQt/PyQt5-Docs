.. sip:class-description::
    :status: todo
    :brief: Timer events for objects
    :digest: e4ef7cfc3214dfd3fd1f0f6b7869da76

The :sip:ref:`~PyQt5.QtCore.QBasicTimer` class provides timer events for objects.

This is a fast, lightweight, and low-level class used by Qt internally. We recommend using the higher-level :sip:ref:`~PyQt5.QtCore.QTimer` class rather than this class if you want to use timers in your applications. Note that this timer is a repeating timer that will send subsequent timer events unless the :sip:ref:`~PyQt5.QtCore.QBasicTimer.stop` function is called.

To use this class, create a :sip:ref:`~PyQt5.QtCore.QBasicTimer`, and call its :sip:ref:`~PyQt5.QtCore.QBasicTimer.start` function with a timeout interval and with a pointer to a :sip:ref:`~PyQt5.QtCore.QObject` subclass. When the timer times out it will send a timer event to the :sip:ref:`~PyQt5.QtCore.QObject` subclass. The timer can be stopped at any time using :sip:ref:`~PyQt5.QtCore.QBasicTimer.stop`. :sip:ref:`~PyQt5.QtCore.QBasicTimer.isActive` returns ``true`` for a timer that is running; i.e. it has been started, has not reached the timeout time, and has not been stopped. The timer's ID can be retrieved using :sip:ref:`~PyQt5.QtCore.QBasicTimer.timerId`.

The `Wiggly <https://doc.qt.io/qt-5/qtwidgets-widgets-wiggly-example.html>`_ example uses :sip:ref:`~PyQt5.QtCore.QBasicTimer` to repaint a widget at regular intervals.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QTimer`, :sip:ref:`~PyQt5.QtCore.QTimerEvent`, :sip:ref:`~PyQt5.QtCore.QObject.timerEvent`, `Timers <https://doc.qt.io/qt-5/timers.html>`_, `Wiggly Example <https://doc.qt.io/qt-5/qtwidgets-widgets-wiggly-example.html>`_.
