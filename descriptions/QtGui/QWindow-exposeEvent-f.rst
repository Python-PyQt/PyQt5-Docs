.. sip:method-description::
    :status: todo
    :pysig: d5e093841b62d8d22cfb758e9107be1e
    :realsig: (QExposeEvent*)
    :digest: ef2f5df45e4e4d7208295cee6d001a14

The expose event (\ *ev*) is sent by the window system whenever an area of the window is invalidated, for example due to the exposure in the windowing system changing.

The application can start rendering into the window with :sip:ref:`~PyQt5.QtGui.QBackingStore` and :sip:ref:`~PyQt5.QtGui.QOpenGLContext` as soon as it gets an  such that :sip:ref:`~PyQt5.QtGui.QWindow.isExposed` is true.

If the window is moved off screen, is made totally obscured by another window, iconified or similar, this function might be called and the value of :sip:ref:`~PyQt5.QtGui.QWindow.isExposed` might change to false. When this happens, an application should stop its rendering as it is no longer visible to the user.

A resize event will always be sent before the expose event the first time a window is shown.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QWindow.isExposed`.
