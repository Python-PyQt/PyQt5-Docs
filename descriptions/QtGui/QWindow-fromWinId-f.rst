.. sip:method-description::
    :status: todo
    :pysig: fa94fdc6e8ff626c0e49ae472877fd01
    :realsig: (WId)
    :digest: 510bb4d8f99aacece334511b8f3a955f

Creates a local representation of a window created by another process or by using native libraries below Qt.

Given the handle *id* to a native window, this method creates a :sip:ref:`~PyQt5.QtGui.QWindow` object which can be used to represent the window when invoking methods like :sip:ref:`~PyQt5.QtGui.QWindow.setParent` and :sip:ref:`~PyQt5.QtGui.QWindow.setTransientParent`.

This can be used, on platforms which support it, to embed a :sip:ref:`~PyQt5.QtGui.QWindow` inside a native window, or to embed a native window inside a :sip:ref:`~PyQt5.QtGui.QWindow`.

If foreign windows are not supported or embedding the native window failed in the platform plugin, this function returns 0.

**Note:** The resulting :sip:ref:`~PyQt5.QtGui.QWindow` should not be used to manipulate the underlying native window (besides re-parenting), or to observe state changes of the native window. Any support for these kind of operations is incidental, highly platform dependent and untested.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QWindow.setParent`, :sip:ref:`~PyQt5.QtGui.QWindow.setTransientParent`.
