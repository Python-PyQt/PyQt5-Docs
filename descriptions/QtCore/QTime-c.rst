.. sip:class-description::
    :status: todo
    :brief: Clock time functions
    :digest: 31845ffbf50ba4b03cd5ce3f9289c3b1

The :sip:ref:`~PyQt5.QtCore.QTime` class provides clock time functions.

A :sip:ref:`~PyQt5.QtCore.QTime` object contains a clock time, which it can express as the numbers of hours, minutes, seconds, and milliseconds since midnight. It can read the current time from the system clock and measure a span of elapsed time. It provides functions for comparing times and for manipulating a time by adding a number of milliseconds.

:sip:ref:`~PyQt5.QtCore.QTime` uses the 24-hour clock format; it has no concept of AM/PM. Unlike :sip:ref:`~PyQt5.QtCore.QDateTime`, :sip:ref:`~PyQt5.QtCore.QTime` knows nothing about time zones or daylight-saving time (DST).

A :sip:ref:`~PyQt5.QtCore.QTime` object is typically created either by giving the number of hours, minutes, seconds, and milliseconds explicitly, or by using the static function :sip:ref:`~PyQt5.QtCore.QTime.currentTime`, which creates a :sip:ref:`~PyQt5.QtCore.QTime` object that contains the system's local time. Note that the accuracy depends on the accuracy of the underlying operating system; not all systems provide 1-millisecond accuracy.

The :sip:ref:`~PyQt5.QtCore.QTime.hour`, :sip:ref:`~PyQt5.QtCore.QTime.minute`, :sip:ref:`~PyQt5.QtCore.QTime.second`, and :sip:ref:`~PyQt5.QtCore.QTime.msec` functions provide access to the number of hours, minutes, seconds, and milliseconds of the time. The same information is provided in textual format by the :sip:ref:`~PyQt5.QtCore.QTime.toString` function.

The :sip:ref:`~PyQt5.QtCore.QTime.addSecs` and :sip:ref:`~PyQt5.QtCore.QTime.addMSecs` functions provide the time a given number of seconds or milliseconds later than a given time. Correspondingly, the number of seconds or milliseconds between two times can be found using :sip:ref:`~PyQt5.QtCore.QTime.secsTo` or :sip:ref:`~PyQt5.QtCore.QTime.msecsTo`.

:sip:ref:`~PyQt5.QtCore.QTime` provides a full set of operators to compare two :sip:ref:`~PyQt5.QtCore.QTime` objects; an earlier time is considered smaller than a later one; if A.\ :sip:ref:`~PyQt5.QtCore.QTime.msecsTo`\ (B) is positive, then A < B.

:sip:ref:`~PyQt5.QtCore.QTime` can be used to measure a span of elapsed time using the :sip:ref:`~PyQt5.QtCore.QTime.start`, :sip:ref:`~PyQt5.QtCore.QTime.restart`, and :sip:ref:`~PyQt5.QtCore.QTime.elapsed` functions.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QDate`, :sip:ref:`~PyQt5.QtCore.QDateTime`.
