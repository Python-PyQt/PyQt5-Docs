.. sip:method-description::
    :status: todo
    :pysig: 941291211259842e1376b76150b50e9d
    :realsig: (QPageLayout::Unit) const
    :digest: bcb0a9c82077ed43706ce04918257bd9

Returns the page rectangle in the required *units*.

The paintable rectangle takes into account the page size, orientation and margins.

If the :sip:ref:`~PyQt5.QtGui.QPageLayout.Mode.FullPageMode` mode is set then the :sip:ref:`~PyQt5.QtGui.QPageLayout.fullRect` is returned and the margins must be manually managed.
