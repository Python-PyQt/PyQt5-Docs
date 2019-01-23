.. sip:method-description::
    :status: todo
    :pysig: 4645aacb161d166c8d3e03fe5d85acc0
    :realsig: (QEvent*)
    :digest: 336abc655e4cbbd6732d04f39ba83369

This virtual function receives events to an object and should return true if the event *e* was recognized and processed.

The  function can be reimplemented to customize the behavior of an object.

Make sure you call the parent event class implementation for all the events you did not handle.

Example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_kernel_qobject.py
    :lines: 505-528

.. seealso:: :sip:ref:`~PyQt5.QtCore.QObject.installEventFilter`, :sip:ref:`~PyQt5.QtCore.QObject.timerEvent`, :sip:ref:`~PyQt5.QtCore.QCoreApplication.sendEvent`, :sip:ref:`~PyQt5.QtCore.QCoreApplication.postEvent`.
