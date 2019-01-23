.. sip:class-description::
    :status: todo
    :brief: Manages a collection of QThreads
    :digest: 75a056e5cfb2be36fe50547e0eae3ec1

The :sip:ref:`~PyQt5.QtCore.QThreadPool` class manages a collection of QThreads.

:sip:ref:`~PyQt5.QtCore.QThreadPool` manages and recyles individual :sip:ref:`~PyQt5.QtCore.QThread` objects to help reduce thread creation costs in programs that use threads. Each Qt application has one global :sip:ref:`~PyQt5.QtCore.QThreadPool` object, which can be accessed by calling :sip:ref:`~PyQt5.QtCore.QThreadPool.globalInstance`.

To use one of the :sip:ref:`~PyQt5.QtCore.QThreadPool` threads, subclass :sip:ref:`~PyQt5.QtCore.QRunnable` and implement the run() virtual function. Then create an object of that class and pass it to :sip:ref:`~PyQt5.QtCore.QThreadPool.start`.

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_concurrent_qthreadpool.py
    :lines: 54-64

:sip:ref:`~PyQt5.QtCore.QThreadPool` deletes the :sip:ref:`~PyQt5.QtCore.QRunnable` automatically by default. Use :sip:ref:`~PyQt5.QtCore.QRunnable.setAutoDelete` to change the auto-deletion flag.

:sip:ref:`~PyQt5.QtCore.QThreadPool` supports executing the same :sip:ref:`~PyQt5.QtCore.QRunnable` more than once by calling :sip:ref:`~PyQt5.QtCore.QThreadPool.tryStart`\ (this) from within :sip:ref:`~PyQt5.QtCore.QRunnable.run`. If autoDelete is enabled the :sip:ref:`~PyQt5.QtCore.QRunnable` will be deleted when the last thread exits the run function. Calling :sip:ref:`~PyQt5.QtCore.QThreadPool.start` multiple times with the same :sip:ref:`~PyQt5.QtCore.QRunnable` when autoDelete is enabled creates a race condition and is not recommended.

Threads that are unused for a certain amount of time will expire. The default expiry timeout is 30000 milliseconds (30 seconds). This can be changed using :sip:ref:`~PyQt5.QtCore.QThreadPool.setExpiryTimeout`. Setting a negative expiry timeout disables the expiry mechanism.

Call :sip:ref:`~PyQt5.QtCore.QThreadPool.maxThreadCount` to query the maximum number of threads to be used. If needed, you can change the limit with :sip:ref:`~PyQt5.QtCore.QThreadPool.setMaxThreadCount`. The default :sip:ref:`~PyQt5.QtCore.QThreadPool.maxThreadCount` is :sip:ref:`~PyQt5.QtCore.QThread.idealThreadCount`. The :sip:ref:`~PyQt5.QtCore.QThreadPool.activeThreadCount` function returns the number of threads currently doing work.

The :sip:ref:`~PyQt5.QtCore.QThreadPool.reserveThread` function reserves a thread for external use. Use :sip:ref:`~PyQt5.QtCore.QThreadPool.releaseThread` when your are done with the thread, so that it may be reused. Essentially, these functions temporarily increase or reduce the active thread count and are useful when implementing time-consuming operations that are not visible to the :sip:ref:`~PyQt5.QtCore.QThreadPool`.

Note that :sip:ref:`~PyQt5.QtCore.QThreadPool` is a low-level class for managing threads, see the Qt Concurrent module for higher level alternatives.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QRunnable`.
