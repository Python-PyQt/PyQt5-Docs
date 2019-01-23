.. sip:method-description::
    :status: todo
    :pysig: c506ff134babdd6e68ab3e6350e95305
    :realsig: () const
    :digest: b701e41b9a6c5cee8204d2840023d99b

Returns if this window is exposed in the windowing system.

When the window is not exposed, it is shown by the application but it is still not showing in the windowing system, so the application should minimize rendering and other graphical activities.

An :sip:ref:`~PyQt5.QtGui.QWindow.exposeEvent` is sent every time this value changes.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QWindow.exposeEvent`.
