.. sip:method-description::
    :status: todo
    :pysig: 0a9fd02b73b00a84b844e2029b59c962
    :realsig: (const QRegion&)
    :digest: bfd296092a23c85d2b1b9cf0c557ec7d

Sets the mask of the window.

The mask is a hint to the windowing system that the application does not want to receive mouse or touch input outside the given *region*.

The window manager may or may not choose to display any areas of the window not included in the mask, thus it is the application's responsibility to clear to transparent the areas that are not part of the mask.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QWindow.mask`.
