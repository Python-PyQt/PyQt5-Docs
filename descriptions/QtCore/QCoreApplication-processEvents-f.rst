.. sip:method-description::
    :status: todo
    :pysig: 79c7f7a794c3902ce78170f84ddba864
    :realsig: (QEventLoop::ProcessEventsFlags)
    :digest: 64c412ad5d660f3882c703d4bd6dfa7c

Processes all pending events for the calling thread according to the specified *flags* until there are no more events to process.

You can call this function occasionally when your program is busy performing a long operation (e.g. copying a file).

In the event that you are running a local loop which calls this function continuously, without an event loop, the :sip:ref:`~PyQt5.QtCore.QEvent.Type.DeferredDelete` events will not be processed. This can affect the behaviour of widgets, e.g. QToolTip, that rely on :sip:ref:`~PyQt5.QtCore.QEvent.Type.DeferredDelete` events to function properly. An alternative would be to call :sip:ref:`~PyQt5.QtCore.QCoreApplication.sendPostedEvents` from within that local loop.

Calling this function processes events only for the calling thread.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QCoreApplication.exec`, :sip:ref:`~PyQt5.QtCore.QTimer`, :sip:ref:`~PyQt5.QtCore.QEventLoop.processEvents`, :sip:ref:`~PyQt5.QtCore.flush`, :sip:ref:`~PyQt5.QtCore.QCoreApplication.sendPostedEvents`.
