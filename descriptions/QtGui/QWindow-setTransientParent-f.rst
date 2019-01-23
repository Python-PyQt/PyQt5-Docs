.. sip:method-description::
    :status: todo
    :pysig: bcb97bdfa32167364bc153e09a7ecb14
    :realsig: (QWindow*)
    :digest: 35038cfed54f375497f40ed1c128043f

Sets the transient *parent*

This is a hint to the window manager that this window is a dialog or pop-up on behalf of the given window.

In order to cause the window to be centered above its transient parent by default, depending on the window manager, it may also be necessary to call :sip:ref:`~PyQt5.QtGui.QWindow.setFlags` with a suitable :sip:ref:`~PyQt5.QtCore.Qt.WindowType` (such as ``Qt::Dialog``).

.. seealso:: :sip:ref:`~PyQt5.QtGui.QWindow.transientParent`, :sip:ref:`~PyQt5.QtGui.QWindow.parent`.
