.. sip:method-description::
    :status: todo
    :pysig: fa7153f7ed1cb6c0fcf2ffb2fac21748
    :realsig: ()
    :digest: 1eab256c67b6fb905d36704fb6b9b3fc

Sets this time to the current time and returns the number of milliseconds that have elapsed since the last time :sip:ref:`~PyQt5.QtCore.QTime.start` or  was called.

This function is guaranteed to be atomic and is thus very handy for repeated measurements. Call :sip:ref:`~PyQt5.QtCore.QTime.start` to start the first measurement, and  for each later measurement.

Note that the counter wraps to zero 24 hours after the last call to :sip:ref:`~PyQt5.QtCore.QTime.start` or .

**Warning:** If the system's clock setting has been changed since the last time :sip:ref:`~PyQt5.QtCore.QTime.start` or  was called, the result is undefined. This can happen when daylight-saving time is turned on or off.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QTime.start`, :sip:ref:`~PyQt5.QtCore.QTime.elapsed`, :sip:ref:`~PyQt5.QtCore.QTime.currentTime`.
