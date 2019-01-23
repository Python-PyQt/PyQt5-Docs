.. sip:class-description::
    :status: todo
    :brief: Exception-safe wrapper around QObject::blockSignals()
    :digest: 082cb2505fb59e2be04976163378af4f

Exception-safe wrapper around :sip:ref:`~PyQt5.QtCore.QObject.blockSignals`.

:sip:ref:`~PyQt5.QtCore.QSignalBlocker` can be used wherever you would otherwise use a pair of calls to blockSignals(). It blocks signals in its constructor and in the destructor it resets the state to what it was before the constructor ran.

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_kernel_qobject.py
    :lines: 545-548

is thus equivalent to

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_kernel_qobject.py
    :lines: 552-554

except the code using :sip:ref:`~PyQt5.QtCore.QSignalBlocker` is safe in the face of exceptions.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QMutexLocker`, :sip:ref:`~PyQt5.QtCore.QEventLoopLocker`.
