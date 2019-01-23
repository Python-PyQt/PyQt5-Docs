.. sip:method-description::
    :status: todo
    :pysig: 37d8abbe73970ad3c2042713396fd379
    :realsig: (QWindow*)
    :digest: eacacaa2a6395ca2fc826ebf89d2e51e

Resets the glass frame and restores the *window* attributes.

This convenience function calls :sip:ref:`~PyQt5.QtWinExtras.QtWin.extendFrameIntoClientArea` with margins set to 0.

**Note:** You must unset the :sip:ref:`~PyQt5.QtCore.Qt.WidgetAttribute.WA_NoSystemBackground` attribute for :sip:ref:`~PyQt5.QtWinExtras.QtWin.extendFrameIntoClientArea` to work.

.. seealso:: :sip:ref:`~PyQt5.QtWinExtras.QtWin.extendFrameIntoClientArea`.
