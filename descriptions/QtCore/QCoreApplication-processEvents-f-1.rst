.. sip:method-description::
    :status: todo
    :pysig: 602dd9c2cd609df0109449ce3b90c07f
    :realsig: (QEventLoop::ProcessEventsFlags,int)
    :digest: 2869376efcad436fa329acf0c697c3ac

This function overloads :sip:ref:`~PyQt5.QtCore.QCoreApplication.processEvents`.

Processes pending events for the calling thread for *maxtime* milliseconds or until there are no more events to process, whichever is shorter.

You can call this function occasionally when your program is busy doing a long operation (e.g. copying a file).

Calling this function processes events only for the calling thread.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QCoreApplication.exec`, :sip:ref:`~PyQt5.QtCore.QTimer`, :sip:ref:`~PyQt5.QtCore.QEventLoop.processEvents`.
