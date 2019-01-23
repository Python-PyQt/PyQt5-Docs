.. sip:method-description::
    :status: todo
    :pysig: e96d1195860ab6e2434cc8b3c8ce444d
    :realsig: (const QSize&,const QString&,QPageSize::SizeMatchPolicy)
    :digest: d33d078269e11053ee8bd02ae7611e29

Creates a :sip:ref:`~PyQt5.QtGui.QPageSize` of the given *pointSize* in Points using the matching *matchPolicy*.

If the given *pointSize* matches a standard :sip:ref:`~PyQt5.QtGui.QPageSize.PageSizeId`, then that page size will be used. Note that if the *matchPolicy* is :sip:ref:`~PyQt5.QtGui.QPageSize.SizeMatchPolicy.FuzzyMatch` this may result in the *pointSize* being adjusted to the standard size. To prevent this happening use a *matchPolicy* of :sip:ref:`~PyQt5.QtGui.QPageSize.SizeMatchPolicy.ExactMatch` instead.

If the given *pointSize* is not a standard :sip:ref:`~PyQt5.QtGui.QPageSize.PageSizeId` then a :sip:ref:`~PyQt5.QtGui.QPageSize.PageSizeId.Custom` size will be created.

If *name* is null then the standard localized name will be used. If a custom page size then a custom name in the format "Custom (width x height)" will be created.

The *matchPolicy* defaults to :sip:ref:`~PyQt5.QtGui.QPageSize.SizeMatchPolicy.FuzzyMatch`.
