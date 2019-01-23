.. sip:method-description::
    :status: todo
    :pysig: 341be97d9aff90c9978347f66f945b77
    :realsig: (const char*)
    :digest: b186bce48999bbaacc264aac95c61aaa

Calls the message handler with the fatal message *message*. If no message handler has been installed, the message is printed to stderr. Under Windows, the message is sent to the debugger. On QNX the message is sent to slogger2.

If you are using the **default message handler** this function will abort to create a core dump. On Windows, for debug builds, this function will report a _CRT_ERROR enabling you to connect a debugger to the application.

This function takes a format string and a list of arguments, similar to the C printf() function.

Example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_global_qglobal.py
    :lines: 363-368

To suppress the output at runtime, install your own message handler with qInstallMessageHandler().

.. seealso:: :sip:ref:`~PyQt5.QtCore.qDebug`, :sip:ref:`~PyQt5.QtCore.qInfo`, :sip:ref:`~PyQt5.QtCore.qWarning`, :sip:ref:`~PyQt5.QtCore.qCritical`.
