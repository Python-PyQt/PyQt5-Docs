.. sip:method-description::
    :status: todo
    :pysig: 5d35e8a8886eed90646ab1e25eaf6516
    :realsig: (QEventLoop::ProcessEventsFlags)
    :digest: a07c6379815b9674b21072ac320f6b0f

Enters the main event loop and waits until :sip:ref:`~PyQt5.QtCore.QEventLoop.exit` is called. Returns the value that was passed to :sip:ref:`~PyQt5.QtCore.QEventLoop.exit`.

If *flags* are specified, only events of the types allowed by the *flags* will be processed.

It is necessary to call this function to start event handling. The main event loop receives events from the window system and dispatches these to the application widgets.

Generally speaking, no user interaction can take place before calling . As a special case, modal widgets like QMessageBox can be used before calling , because modal widgets use their own local event loop.

To make your application perform idle processing (i.e. executing a special function whenever there are no pending events), use a :sip:ref:`~PyQt5.QtCore.QTimer` with 0 timeout. More sophisticated idle processing schemes can be achieved using :sip:ref:`~PyQt5.QtCore.QEventLoop.processEvents`.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QCoreApplication.quit`, :sip:ref:`~PyQt5.QtCore.QEventLoop.exit`, :sip:ref:`~PyQt5.QtCore.QEventLoop.processEvents`.
