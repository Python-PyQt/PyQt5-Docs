.. sip:method-description::
    :status: todo
    :pysig: 677f77598a3541166fd0645412ecb9d9
    :realsig: (QMutex::RecursionMode)
    :digest: 1fd2b82afd1ff8e537d9a288bca2b4a6

Constructs a new mutex. The mutex is created in an unlocked state.

If *mode* is :sip:ref:`~PyQt5.QtCore.QMutex.RecursionMode.Recursive`, a thread can lock the same mutex multiple times and the mutex won't be unlocked until a corresponding number of :sip:ref:`~PyQt5.QtCore.QMutex.unlock` calls have been made. Otherwise a thread may only lock a mutex once. The default is :sip:ref:`~PyQt5.QtCore.QMutex.RecursionMode.NonRecursive`.

Recursive mutexes are slower and take more memory than non-recursive ones.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QMutex.lock`, :sip:ref:`~PyQt5.QtCore.QMutex.unlock`.
