.. sip:method-description::
    :status: todo
    :pysig: bcb97bdfa32167364bc153e09a7ecb14
    :realsig: (QWindow*)
    :digest: 782b1fae09186dd4750007fa87164d1d

Sets the *parent* Window. This will lead to the windowing system managing the clip of the window, so it will be clipped to the *parent* window.

Setting *parent* to be 0 will make the window become a top level window.

If *parent* is a window created by :sip:ref:`~PyQt5.QtGui.QWindow.fromWinId`, then the current window will be embedded inside *parent*, if the platform supports it.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QWindow.parent`.
