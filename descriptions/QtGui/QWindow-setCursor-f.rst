.. sip:method-description::
    :status: todo
    :pysig: 00cf055c72111697a1ed8b2d20de13de
    :realsig: (const QCursor&)
    :digest: 637158724c06b2edcbc4f036cb30ddff

set the cursor shape for this window

The mouse *cursor* will assume this shape when it is over this window, unless an override cursor is set. See the :sip:ref:`~PyQt5.QtCore.Qt.CursorShape` for a range of useful shapes.

If no cursor has been set, or after a call to :sip:ref:`~PyQt5.QtGui.QWindow.unsetCursor`, the parent window's cursor is used.

By default, the cursor has the :sip:ref:`~PyQt5.QtCore.Qt.CursorShape.ArrowCursor` shape.

Some underlying window implementations will reset the cursor if it leaves a window even if the mouse is grabbed. If you want to have a cursor set for all windows, even when outside the window, consider :sip:ref:`~PyQt5.QtGui.QGuiApplication.setOverrideCursor`.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QWindow.cursor`, :sip:ref:`~PyQt5.QtGui.QGuiApplication.setOverrideCursor`.
