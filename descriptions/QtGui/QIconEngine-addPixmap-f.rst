.. sip:method-description::
    :status: todo
    :pysig: b984b3ebe897c8411e6c84f84df66937
    :realsig: (const QPixmap&,QIcon::Mode,QIcon::State)
    :digest: 95a2f48210de2631ecdaa9308119e67b

Called by :sip:ref:`~PyQt5.QtGui.QIcon.addPixmap`. Adds a specialized *pixmap* for the given *mode* and *state*. The default pixmap-based engine stores any supplied pixmaps, and it uses them instead of scaled pixmaps if the size of a pixmap matches the size of icon requested. Custom icon engines that implement scalable vector formats are free to ignores any extra pixmaps.
