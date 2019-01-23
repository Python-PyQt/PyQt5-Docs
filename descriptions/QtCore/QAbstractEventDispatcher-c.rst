.. sip:class-description::
    :status: todo
    :brief: Interface to manage Qt's event queue
    :digest: 15783398b7823f42c73d46bfe0ae1ad8

The :sip:ref:`~PyQt5.QtCore.QAbstractEventDispatcher` class provides an interface to manage Qt's event queue.

An event dispatcher receives events from the window system and other sources. It then sends them to the :sip:ref:`~PyQt5.QtCore.QCoreApplication` or QApplication instance for processing and delivery. :sip:ref:`~PyQt5.QtCore.QAbstractEventDispatcher` provides fine-grained control over event delivery.

For simple control of event processing use :sip:ref:`~PyQt5.QtCore.QCoreApplication.processEvents`.

For finer control of the application's event loop, call :sip:ref:`~PyQt5.QtCore.QAbstractEventDispatcher.instance` and call functions on the :sip:ref:`~PyQt5.QtCore.QAbstractEventDispatcher` object that is returned. If you want to use your own instance of :sip:ref:`~PyQt5.QtCore.QAbstractEventDispatcher` or of a :sip:ref:`~PyQt5.QtCore.QAbstractEventDispatcher` subclass, you must install it with QCoreApplication::setEventDispatcher() or QThread::setEventDispatcher() *before* a default event dispatcher has been installed.

The main event loop is started by calling :sip:ref:`~PyQt5.QtCore.QCoreApplication.exec`, and stopped by calling :sip:ref:`~PyQt5.QtCore.QCoreApplication.exit`. Local event loops can be created using :sip:ref:`~PyQt5.QtCore.QEventLoop`.

Programs that perform long operations can call :sip:ref:`~PyQt5.QtCore.QAbstractEventDispatcher.processEvents` with a bitwise OR combination of various :sip:ref:`~PyQt5.QtCore.QEventLoop.ProcessEventsFlag` values to control which events should be delivered.

:sip:ref:`~PyQt5.QtCore.QAbstractEventDispatcher` also allows the integration of an external event loop with the Qt event loop.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QEventLoop`, :sip:ref:`~PyQt5.QtCore.QCoreApplication`, :sip:ref:`~PyQt5.QtCore.QThread`.
