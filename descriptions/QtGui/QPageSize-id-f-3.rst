.. sip:method-description::
    :status: todo
    :pysig: 6c1ddc549ad5456ec13b44154d934fbe
    :realsig: (const QSizeF&,QPageSize::Unit,QPageSize::SizeMatchPolicy)
    :digest: 94a32163b0cfffc053cb3cd2b16446aa

Returns the standard :sip:ref:`~PyQt5.QtGui.QPageSize.PageSizeId` of the given *size* in *units* using the given *matchPolicy*.

If using :sip:ref:`~PyQt5.QtGui.QPageSize.SizeMatchPolicy.FuzzyMatch` then the unit size of the :sip:ref:`~PyQt5.QtGui.QPageSize.PageSizeId.PageSizeId` returned may not exactly match the *size* you passed in. You should call QPageSize::size() using the returned :sip:ref:`~PyQt5.QtGui.QPageSize.PageSizeId.PageSizeId` to find out the actual unit size of the :sip:ref:`~PyQt5.QtGui.QPageSize.PageSizeId.PageSizeId` before using it in any calculations.
