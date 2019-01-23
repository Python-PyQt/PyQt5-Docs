.. sip:method-description::
    :status: todo
    :pysig: 271edd5e2bd089c8749a319b3637d3e6
    :realsig: () const
    :digest: ce1a59f4c9e51e9e0d9ff4e4f3de2ad0

Returns the current maximum size of the device coordinate cache for this item. If the item is cached using QGraphicsItem::DeviceCoordinateCache mode, caching is bypassed if the extension of the item in device coordinates is larger than the maximum size.

The default maximum cache size is 1024x768. :sip:ref:`~PyQt5.QtGui.QPixmapCache.cacheLimit` gives the cumulative bounds of the whole cache, whereas  refers to a maximum cache size for this particular item.

.. seealso:: :sip:ref:`~PyQt5.QtWidgets.QGraphicsItem.cacheMode`.
