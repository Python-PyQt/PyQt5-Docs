.. sip:method-description::
    :status: todo
    :pysig: 271edd5e2bd089c8749a319b3637d3e6
    :realsig: (const QSize&)
    :digest: 9b9fc522eca2352039efdf0a3f40042f

Sets the size increment (\ *size*) of the window.

When the user resizes the window, the size will move in steps of :sip:ref:`~PyQt5.QtGui.QWindow.sizeIncrement`.\ :sip:ref:`~PyQt5.QtGui.QWindow.width` pixels horizontally and :sip:ref:`~PyQt5.QtGui.QWindow.sizeIncrement`.\ :sip:ref:`~PyQt5.QtGui.QWindow.height` pixels vertically, with :sip:ref:`~PyQt5.QtGui.QWindow.baseSize` as the basis.

By default, this property contains a size with zero width and height.

The windowing system might not support size increments.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QWindow.sizeIncrement`, :sip:ref:`~PyQt5.QtGui.QWindow.setBaseSize`, :sip:ref:`~PyQt5.QtGui.QWindow.setMinimumSize`, :sip:ref:`~PyQt5.QtGui.QWindow.setMaximumSize`.
