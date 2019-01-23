.. sip:method-description::
    :status: todo
    :pysig: a814207385abadf28f1ebc9643534ff6
    :realsig: (QEvent::Type,const QPoint&,const QPoint&)
    :digest: 38b5bf314d0c5770be5b59ad8e323a15

Constructs a help event with the given *type* corresponding to the widget-relative position specified by *pos* and the global position specified by *globalPos*.

*type* must be either :sip:ref:`~PyQt5.QtCore.QEvent.Type.ToolTip` or :sip:ref:`~PyQt5.QtCore.QEvent.Type.WhatsThis`.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QHelpEvent.pos`, :sip:ref:`~PyQt5.QtGui.QHelpEvent.globalPos`.
