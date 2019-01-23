.. sip:method-description::
    :status: todo
    :pysig: 8f7b6e06f895ac5e3dc539eafd02a664
    :realsig: (QRunnable*)
    :digest: 4c299c12bec66affc6f066f0b77e2805

Attempts to reserve a thread to run *runnable*.

If no threads are available at the time of calling, then this function does nothing and returns ``false``. Otherwise, *runnable* is run immediately using one available thread and this function returns ``true``.

Note that the thread pool takes ownership of the *runnable* if :sip:ref:`~PyQt5.QtCore.QRunnable.autoDelete` returns ``true``, and the *runnable* will be deleted automatically by the thread pool after the :sip:ref:`~PyQt5.QtCore.QRunnable.run` returns. If :sip:ref:`~PyQt5.QtCore.QRunnable.autoDelete` returns ``false``, ownership of *runnable* remains with the caller. Note that changing the auto-deletion on *runnable* after calling this function results in undefined behavior.
