.. sip:enum-member-description::
    :status: todo
    :value: TODO
    :digest: 5618d18f781dd95f68e9ae6c396bbefd

Make :sip:ref:`~PyQt5.QtGui.QIcon.pixmap` generate high-dpi pixmaps that can be larger than the requested size. Such pixmaps will have devicePixelRatio() set to a value higher than 1. After setting this attribute, application code that uses pixmap sizes in layout geometry calculations should typically divide by devicePixelRatio() to get device-independent layout geometry.
