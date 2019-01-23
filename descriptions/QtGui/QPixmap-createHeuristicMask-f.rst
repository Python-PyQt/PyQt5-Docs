.. sip:method-description::
    :status: todo
    :pysig: d160ede9d2b5a736adf972a2dcafe1fa
    :realsig: (bool) const
    :digest: 753f86fd6c188c4989a55e862552777f

Creates and returns a heuristic mask for this pixmap.

The function works by selecting a color from one of the corners and then chipping away pixels of that color, starting at all the edges. If *clipTight* is true (the default) the mask is just large enough to cover the pixels; otherwise, the mask is larger than the data pixels.

The mask may not be perfect but it should be reasonable, so you can do things such as the following:

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-code-src_gui_image_qpixmap.py
    :lines: 62-63

This function is slow because it involves converting to/from a :sip:ref:`~PyQt5.QtGui.QImage`, and non-trivial computations.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPixmap.createMaskFromColor`, :sip:ref:`~PyQt5.QtGui.QImage.createHeuristicMask`.
