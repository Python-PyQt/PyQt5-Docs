.. sip:method-description::
    :status: todo
    :pysig: 3c57b0cc90800102499738b21d30f66e
    :realsig: (QWindow*,int,int,int,int)
    :digest: 16858d7e9f3f6ed20bfb6f6c33b0f425

Extends the glass frame into the client area of the specified *window* using the *left*, *top*, *right*, and *bottom* margin values.

Pass -1 as values for any of the four margins to fully extend the frame, creating a *sheet of glass* effect.

If you want the extended frame to act like a standard window border, you should handle that yourself.

**Note:** If *window* is a :sip:ref:`~PyQt5.QtWidgets.QWidget` handle, set the :sip:ref:`~PyQt5.QtCore.Qt.WidgetAttribute.WA_NoSystemBackground` attribute for your widget.

.. seealso:: :sip:ref:`~PyQt5.QtWinExtras.QtWin.resetExtendedFrame`.
