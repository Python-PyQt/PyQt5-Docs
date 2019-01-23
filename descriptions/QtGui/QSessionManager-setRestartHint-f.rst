.. sip:method-description::
    :status: todo
    :pysig: 945fe3a06ae98a6758d2bd1daf74a253
    :realsig: (QSessionManager::RestartHint)
    :digest: 1e1c7ddae45229149a695ad99ea25b39

Sets the application's restart hint to *hint*. On application startup, the hint is set to ``RestartIfRunning``.

**Note:** These flags are only hints, a session manager may or may not respect them.

We recommend setting the restart hint in :sip:ref:`~PyQt5.QtGui.QGuiApplication.saveStateRequest` because most session managers perform a checkpoint shortly after an application's startup.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QSessionManager.restartHint`.
