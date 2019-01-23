.. sip:method-description::
    :status: todo
    :pysig: 0f42e85db8b6634d55c1dd1d63042a1f
    :realname: QDrag::exec
    :realsig: (Qt::DropActions,Qt::DropAction)
    :digest: 4f4ec327abfae4982d2ae31e8607573f

Starts the drag and drop operation and returns a value indicating the requested drop action when it is completed. The drop actions that the user can choose from are specified in *supportedActions*.

The *defaultDropAction* determines which action will be proposed when the user performs a drag without using modifier keys.

**Note:** On Linux and `macOS <https://doc.qt.io/qt-5/qtwebengine-platform-notes.html#macos>`_, the drag and drop operation can take some time, but this function does not block the event loop. Other events are still delivered to the application while the operation is performed. On Windows, the Qt event loop is blocked during the operation. However, :sip:ref:`~PyQt5.QtGui.QDrag.exec` on Windows causes processEvents() to be called frequently to keep the GUI responsive. If any loops or operations are called while a drag operation is active, it will block the drag operation.
