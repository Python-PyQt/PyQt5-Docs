.. sip:class-description::
    :status: todo
    :brief: Convenience class that simplifies locking and unlocking mutexes
    :digest: e979bf78efa06a3aff7ec5bc9fb46c69

The :sip:ref:`~PyQt5.QtCore.QMutexLocker` class is a convenience class that simplifies locking and unlocking mutexes.

Locking and unlocking a :sip:ref:`~PyQt5.QtCore.QMutex` in complex functions and statements or in exception handling code is error-prone and difficult to debug. :sip:ref:`~PyQt5.QtCore.QMutexLocker` can be used in such situations to ensure that the state of the mutex is always well-defined.

:sip:ref:`~PyQt5.QtCore.QMutexLocker` should be created within a function where a :sip:ref:`~PyQt5.QtCore.QMutex` needs to be locked. The mutex is locked when :sip:ref:`~PyQt5.QtCore.QMutexLocker` is created. You can unlock and relock the mutex with ``unlock()`` and ``relock()``. If locked, the mutex will be unlocked when the :sip:ref:`~PyQt5.QtCore.QMutexLocker` is destroyed.

For example, this complex function locks a :sip:ref:`~PyQt5.QtCore.QMutex` upon entering the function and unlocks the mutex at all the exit points:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_thread_qmutex.py
    :lines: 120-151

This example function will get more complicated as it is developed, which increases the likelihood that errors will occur.

Using :sip:ref:`~PyQt5.QtCore.QMutexLocker` greatly simplifies the code, and makes it more readable:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_thread_qmutex.py
    :lines: 156-181

Now, the mutex will always be unlocked when the :sip:ref:`~PyQt5.QtCore.QMutexLocker` object is destroyed (when the function returns since ``locker`` is an auto variable).

The same principle applies to code that throws and catches exceptions. An exception that is not caught in the function that has locked the mutex has no way of unlocking the mutex before the exception is passed up the stack to the calling function.

:sip:ref:`~PyQt5.QtCore.QMutexLocker` also provides a ``mutex()`` member function that returns the mutex on which the :sip:ref:`~PyQt5.QtCore.QMutexLocker` is operating. This is useful for code that needs access to the mutex, such as :sip:ref:`~PyQt5.QtCore.QWaitCondition.wait`. For example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_thread_qmutex.py
    :lines: 186-204

.. seealso:: :sip:ref:`~PyQt5.QtCore.QReadLocker`, :sip:ref:`~PyQt5.QtCore.QWriteLocker`, :sip:ref:`~PyQt5.QtCore.QMutex`.
