.. sip:method-description::
    :status: todo
    :pysig: cd756c5b6e9231f18958d85978fd7238
    :realsig: (int)
    :digest: cbab8bfd688765dc082d41200afa3a5d

Releases *n* resources guarded by the semaphore.

This function can be used to "create" resources as well. For example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_thread_qsemaphore.py
    :lines: 67-70

:sip:ref:`~PyQt5.QtCore.QSemaphoreReleaser` is a RAII wrapper around this function.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QSemaphore.acquire`, :sip:ref:`~PyQt5.QtCore.QSemaphore.available`, :sip:ref:`~PyQt5.QtCore.QSemaphoreReleaser`.
