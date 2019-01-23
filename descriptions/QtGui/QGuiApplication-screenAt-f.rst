.. sip:method-description::
    :status: todo
    :pysig: 95391873c315a43cd02cbaad78679a96
    :realsig: (const QPoint&)
    :digest: 1256ba34da88a644c456f5c349105c1c

Returns the screen at *point*, or ``nullptr`` if outside of any screen.

The *point* is in relation to the virtualGeometry() of each set of virtual siblings. If the point maps to more than one set of virtual siblings the first match is returned.
