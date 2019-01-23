.. sip:method-description::
    :status: todo
    :pysig: 548b569e6a25c44ebb536c7262614674
    :realsig: (const QPainterPath&) const
    :digest: 269eb16e55650b655113bc8af9275cbb

Returns a path which is the union of this path's fill area and *p*'s fill area.

Set operations on paths will treat the paths as areas. Non-closed paths will be treated as implicitly closed. Bezier curves may be flattened to line segments due to numerical instability of doing bezier curve intersections.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPainterPath.intersected`, :sip:ref:`~PyQt5.QtGui.QPainterPath.subtracted`.
