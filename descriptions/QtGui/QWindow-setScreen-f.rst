.. sip:method-description::
    :status: todo
    :pysig: dfd85e174626516c7c9700b91423ab63
    :realsig: (QScreen*)
    :digest: a548856f8f2262551f03995ca01f454d

Sets the screen on which the window should be shown.

If the window has been created, it will be recreated on the *newScreen*.

**Note:** If the screen is part of a virtual desktop of multiple screens, the window will not move automatically to *newScreen*. To place the window relative to the screen, use the screen's `topLeft() <https://doc.qt.io/qt-5/qml-georectangle.html#topleft>`_ position.

This function only works for top level windows.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QWindow.screen`, :sip:ref:`~PyQt5.QtGui.QScreen.virtualSiblings`.
