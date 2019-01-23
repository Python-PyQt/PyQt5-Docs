.. sip:method-description::
    :status: todo
    :pysig: c506ff134babdd6e68ab3e6350e95305
    :realsig: ()
    :digest: 7e7649eb349a96938426e39ecc383a62

Close the window.

This closes the window, effectively calling :sip:ref:`~PyQt5.QtGui.QWindow.destroy`, and potentially quitting the application. Returns ``true`` on success, false if it has a parent window (in which case the top level window should be closed instead).

.. seealso:: :sip:ref:`~PyQt5.QtGui.QWindow.destroy`, :sip:ref:`~PyQt5.QtGui.QGuiApplication.quitOnLastWindowClosed`.
