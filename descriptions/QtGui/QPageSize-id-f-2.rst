.. sip:method-description::
    :status: todo
    :pysig: 62dcc3419fcde3467df4e44ffacaf73d
    :realsig: (const QSize&,QPageSize::SizeMatchPolicy)
    :digest: 65f681da00e8922300e2dd56570ff960

Returns the standard :sip:ref:`~PyQt5.QtGui.QPageSize.PageSizeId` of the given *pointSize* in points using the given *matchPolicy*.

If using :sip:ref:`~PyQt5.QtGui.QPageSize.SizeMatchPolicy.FuzzyMatch` then the point size of the :sip:ref:`~PyQt5.QtGui.QPageSize.PageSizeId.PageSizeId` returned may not exactly match the *pointSize* you passed in. You should call QPageSize::sizePoints() using the returned :sip:ref:`~PyQt5.QtGui.QPageSize.PageSizeId.PageSizeId` to find out the actual point size of the :sip:ref:`~PyQt5.QtGui.QPageSize.PageSizeId.PageSizeId` before using it in any calculations.
