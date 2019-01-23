.. sip:method-description::
    :status: todo
    :pysig: f47408eb42b5118f690e8b04710e7254
    :realsig: (const QColor&,Qt::MaskMode) const
    :digest: ef79421e57c8709d698da765044a1361

Creates and returns a mask for this pixmap based on the given *maskColor*. If the *mode* is :sip:ref:`~PyQt5.QtCore.Qt.MaskMode.MaskInColor`, all pixels matching the maskColor will be transparent. If *mode* is :sip:ref:`~PyQt5.QtCore.Qt.MaskMode.MaskOutColor`, all pixels matching the maskColor will be opaque.

This function is slow because it involves converting to/from a :sip:ref:`~PyQt5.QtGui.QImage`.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPixmap.createHeuristicMask`.
