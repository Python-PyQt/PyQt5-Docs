.. sip:method-description::
    :status: todo
    :pysig: 006a04a16752b4725ee0971709a25844
    :realsig: (Qt::DropActions)
    :digest: 8ab26a03ee045865adc3139fae343ddb

Starts the drag and drop operation and returns a value indicating the requested drop action when it is completed. The drop actions that the user can choose from are specified in *supportedActions*. The default proposed action will be selected among the allowed actions in the following order: Move, Copy and Link.

**Note:** On Linux and `macOS <https://doc.qt.io/qt-5/qtwebengine-platform-notes.html#macos>`_, the drag and drop operation can take some time, but this function does not block the event loop. Other events are still delivered to the application while the operation is performed. On Windows, the Qt event loop is blocked during the operation.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QDrag.cancel`.
