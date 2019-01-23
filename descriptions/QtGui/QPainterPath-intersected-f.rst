.. sip:method-description::
    :status: todo
    :pysig: 548b569e6a25c44ebb536c7262614674
    :realsig: (const QPainterPath&) const
    :digest: e19a054bb949ad69f1f21e81c98f9bbe

Returns a path which is the intersection of this path's fill area and *p*'s fill area. Bezier curves may be flattened to line segments due to numerical instability of doing bezier curve intersections.
