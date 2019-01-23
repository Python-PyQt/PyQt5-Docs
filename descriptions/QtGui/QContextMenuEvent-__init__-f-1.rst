.. sip:method-description::
    :status: todo
    :pysig: 5e620c74c2e34af1749780d4057fa93a
    :realsig: (QContextMenuEvent::Reason,const QPoint&)
    :digest: c1677f9942a6c9fa8f8239357e17fdc3

Constructs a context menu event object with the accept parameter flag set to false.

The *reason* parameter must be :sip:ref:`~PyQt5.QtGui.QContextMenuEvent.Reason.Mouse` or :sip:ref:`~PyQt5.QtGui.QContextMenuEvent.Reason.Keyboard`.

The *pos* parameter specifies the mouse position relative to the receiving widget.

The :sip:ref:`~PyQt5.QtGui.QContextMenuEvent.globalPos` is initialized to QCursor::pos(), which may not be appropriate. Use the other constructor to specify the global position explicitly.
