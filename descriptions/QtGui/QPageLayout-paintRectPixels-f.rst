.. sip:method-description::
    :status: todo
    :pysig: 53f572b9f443da93fc5be49a030e29c7
    :realsig: (int) const
    :digest: f74c95d89b7c7a0dddd2a342dd075aa4

Returns the paintable rectangle in rounded device pixels for the given *resolution*.

The paintable rectangle takes into account the page size, orientation and margins.

If the :sip:ref:`~PyQt5.QtGui.QPageLayout.Mode.FullPageMode` mode is set then the :sip:ref:`~PyQt5.QtGui.QPageLayout.fullRect` is returned and the margins must be manually managed.
