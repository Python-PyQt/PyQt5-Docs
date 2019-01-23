.. sip:method-description::
    :status: todo
    :pysig: 2a25b348a59d87879f518122c6f948a6
    :realsig: () const
    :digest: 631ebb2ea260e1aaa6bc6f6e9f07cf62

Returns the page rectangle in the current layout units.

The paintable rectangle takes into account the page size, orientation and margins.

If the :sip:ref:`~PyQt5.QtGui.QPageLayout.Mode.FullPageMode` mode is set then the :sip:ref:`~PyQt5.QtGui.QPageLayout.fullRect` is returned and the margins must be manually managed.
