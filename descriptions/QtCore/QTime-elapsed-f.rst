.. sip:method-description::
    :status: todo
    :pysig: fa7153f7ed1cb6c0fcf2ffb2fac21748
    :realsig: () const
    :digest: 85a30b39f8cac7dfdf795ab25fdf8bc0

Returns the number of milliseconds that have elapsed since the last time :sip:ref:`~PyQt5.QtCore.QTime.start` or :sip:ref:`~PyQt5.QtCore.QTime.restart` was called.

Note that the counter wraps to zero 24 hours after the last call to :sip:ref:`~PyQt5.QtCore.QTime.start` or restart.

Note that the accuracy depends on the accuracy of the underlying operating system; not all systems provide 1-millisecond accuracy.

**Warning:** If the system's clock setting has been changed since the last time :sip:ref:`~PyQt5.QtCore.QTime.start` or :sip:ref:`~PyQt5.QtCore.QTime.restart` was called, the result is undefined. This can happen when daylight-saving time is turned on or off.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QTime.start`, :sip:ref:`~PyQt5.QtCore.QTime.restart`.
