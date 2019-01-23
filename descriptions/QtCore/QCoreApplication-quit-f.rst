.. sip:method-description::
    :status: todo
    :pysig: a81259cef8e959c624df1d456e5d3297
    :realsig: ()
    :digest: 1aa31bef9b3f9c64021c65482179c32f

Tells the application to exit with return code 0 (success). Equivalent to calling :sip:ref:`~PyQt5.QtCore.QCoreApplication.exit`\ (0).

It's common to connect the :sip:ref:`~PyQt5.QtGui.QGuiApplication.lastWindowClosed` signal to , and you also often connect e.g. QAbstractButton::clicked() or signals in QAction, QMenu, or QMenuBar to it.

It's good practice to always connect signals to this slot using a :sip:ref:`~PyQt5.QtCore.Qt.ConnectionType.QueuedConnection`. If a signal connected (non-queued) to this slot is emitted before control enters the main event loop (such as before "int main" calls :sip:ref:`~PyQt5.QtCore.QCoreApplication.exec`), the slot has no effect and the application never exits. Using a queued connection ensures that the slot will not be invoked until after control enters the main event loop.

Example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_kernel_qcoreapplication.py
    :lines: 60-61

.. seealso:: :sip:ref:`~PyQt5.QtCore.QCoreApplication.exit`, :sip:ref:`~PyQt5.QtCore.QCoreApplication.aboutToQuit`, :sip:ref:`~PyQt5.QtGui.QGuiApplication.lastWindowClosed`.
