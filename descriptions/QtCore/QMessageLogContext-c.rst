.. sip:class-description::
    :status: todo
    :brief: Additional information about a log message
    :digest: cf670eed9a6bd21cd29ed4ccfb2de1d6

The :sip:ref:`~PyQt5.QtCore.QMessageLogContext` class provides additional information about a log message.

The class provides information about the source code location a :sip:ref:`~PyQt5.QtCore.qDebug`, :sip:ref:`~PyQt5.QtCore.qInfo`, :sip:ref:`~PyQt5.QtCore.qWarning`, :sip:ref:`~PyQt5.QtCore.qCritical` or :sip:ref:`~PyQt5.QtCore.qFatal` message was generated.

**Note:** By default, this information is recorded only in debug builds. You can overwrite this explicitly by defining ``QT_MESSAGELOGCONTEXT`` or ``QT_NO_MESSAGELOGCONTEXT``.

.. seealso:: QtMessageHandler, :sip:ref:`~PyQt5.QtCore.QMessageLogger`.
