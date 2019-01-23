.. sip:method-description::
    :status: todo
    :pysig: 3ab5bf060c4718faa40f52c58dc07624
    :realsig: (QContextMenuEvent::Reason,const QPoint&,const QPoint&)
    :digest: 58f9fcfbf0155c3ed3839a8fb28c9bfb

Constructs a context menu event object with the accept parameter flag set to false.

The *reason* parameter must be :sip:ref:`~PyQt5.QtGui.QContextMenuEvent.Reason.Mouse` or :sip:ref:`~PyQt5.QtGui.QContextMenuEvent.Reason.Keyboard`.

The *pos* parameter specifies the mouse position relative to the receiving widget. *globalPos* is the mouse position in absolute coordinates.
