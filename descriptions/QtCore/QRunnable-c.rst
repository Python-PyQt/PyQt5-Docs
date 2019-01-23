.. sip:class-description::
    :status: todo
    :brief: The base class for all runnable objects
    :digest: 8ce9d6168a3a6c87c5f8e301b8b8613a

The :sip:ref:`~PyQt5.QtCore.QRunnable` class is the base class for all runnable objects.

The :sip:ref:`~PyQt5.QtCore.QRunnable` class is an interface for representing a task or piece of code that needs to be executed, represented by your reimplementation of the :sip:ref:`~PyQt5.QtCore.QRunnable.run` function.

You can use :sip:ref:`~PyQt5.QtCore.QThreadPool` to execute your code in a separate thread. :sip:ref:`~PyQt5.QtCore.QThreadPool` deletes the :sip:ref:`~PyQt5.QtCore.QRunnable` automatically if :sip:ref:`~PyQt5.QtCore.QRunnable.autoDelete` returns ``true`` (the default). Use :sip:ref:`~PyQt5.QtCore.QRunnable.setAutoDelete` to change the auto-deletion flag.

:sip:ref:`~PyQt5.QtCore.QThreadPool` supports executing the same :sip:ref:`~PyQt5.QtCore.QRunnable` more than once by calling :sip:ref:`~PyQt5.QtCore.QThreadPool.tryStart`\ (this) from within the :sip:ref:`~PyQt5.QtCore.QRunnable.run` function. If :sip:ref:`~PyQt5.QtCore.QRunnable.autoDelete` is enabled the :sip:ref:`~PyQt5.QtCore.QRunnable` will be deleted when the last thread exits the run function. Calling :sip:ref:`~PyQt5.QtCore.QThreadPool.start` multiple times with the same :sip:ref:`~PyQt5.QtCore.QRunnable` when :sip:ref:`~PyQt5.QtCore.QRunnable.autoDelete` is enabled creates a race condition and is not recommended.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QThreadPool`.
