.. sip:method-description::
    :status: todo
    :pysig: a773719dae5eb8c379b27e2ab6d10f66
    :realsig: (const QSize&,QIcon::Mode,QIcon::State)
    :digest: 083e148b5d71bc348f2d53a9321fc88e

Returns the icon as a pixmap with the required *size*, *mode*, and *state*. The default implementation creates a new pixmap and calls :sip:ref:`~PyQt5.QtGui.QIconEngine.paint` to fill it.
