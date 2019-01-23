.. sip:class-description::
    :status: todo
    :brief: Date and time functions
    :digest: 20ae394c852754db9d7fa3dbdd85f656

The :sip:ref:`~PyQt5.QtCore.QDateTime` class provides date and time functions.

A :sip:ref:`~PyQt5.QtCore.QDateTime` object encodes a calendar date and a clock time (a "datetime"). It combines features of the :sip:ref:`~PyQt5.QtCore.QDate` and :sip:ref:`~PyQt5.QtCore.QTime` classes. It can read the current datetime from the system clock. It provides functions for comparing datetimes and for manipulating a datetime by adding a number of seconds, days, months, or years.

A :sip:ref:`~PyQt5.QtCore.QDateTime` object is typically created either by giving a date and time explicitly in the constructor, or by using the static function :sip:ref:`~PyQt5.QtCore.QDateTime.currentDateTime` that returns a :sip:ref:`~PyQt5.QtCore.QDateTime` object set to the system clock's time. The date and time can be changed with :sip:ref:`~PyQt5.QtCore.QDateTime.setDate` and :sip:ref:`~PyQt5.QtCore.QDateTime.setTime`. A datetime can also be set using the :sip:ref:`~PyQt5.QtCore.QDateTime.setTime_t` function that takes a POSIX-standard "number of seconds since 00:00:00 on January 1, 1970" value. The :sip:ref:`~PyQt5.QtCore.QDateTime.fromString` function returns a :sip:ref:`~PyQt5.QtCore.QDateTime`, given a string and a date format used to interpret the date within the string.

The :sip:ref:`~PyQt5.QtCore.QDateTime.date` and :sip:ref:`~PyQt5.QtCore.QDateTime.time` functions provide access to the date and time parts of the datetime. The same information is provided in textual format by the :sip:ref:`~PyQt5.QtCore.QDateTime.toString` function.

:sip:ref:`~PyQt5.QtCore.QDateTime` provides a full set of operators to compare two :sip:ref:`~PyQt5.QtCore.QDateTime` objects, where smaller means earlier and larger means later.

You can increment (or decrement) a datetime by a given number of milliseconds using :sip:ref:`~PyQt5.QtCore.QDateTime.addMSecs`, seconds using :sip:ref:`~PyQt5.QtCore.QDateTime.addSecs`, or days using :sip:ref:`~PyQt5.QtCore.QDateTime.addDays`. Similarly, you can use :sip:ref:`~PyQt5.QtCore.QDateTime.addMonths` and :sip:ref:`~PyQt5.QtCore.QDateTime.addYears`. The :sip:ref:`~PyQt5.QtCore.QDateTime.daysTo` function returns the number of days between two datetimes, :sip:ref:`~PyQt5.QtCore.QDateTime.secsTo` returns the number of seconds between two datetimes, and :sip:ref:`~PyQt5.QtCore.QDateTime.msecsTo` returns the number of milliseconds between two datetimes.

:sip:ref:`~PyQt5.QtCore.QDateTime` can store datetimes as :sip:ref:`~PyQt5.QtCore.Qt.TimeSpec.LocalTime` or as :sip:ref:`~PyQt5.QtCore.Qt.TimeSpec.UTC`. :sip:ref:`~PyQt5.QtCore.QDateTime.currentDateTime` returns a :sip:ref:`~PyQt5.QtCore.QDateTime` expressed as local time; use :sip:ref:`~PyQt5.QtCore.QDateTime.toUTC` to convert it to UTC. You can also use :sip:ref:`~PyQt5.QtCore.QDateTime.timeSpec` to find out if a :sip:ref:`~PyQt5.QtCore.QDateTime` object stores a UTC time or a local time. Operations such as :sip:ref:`~PyQt5.QtCore.QDateTime.addSecs` and :sip:ref:`~PyQt5.QtCore.QDateTime.secsTo` are aware of daylight-saving time (DST).

**Note:** :sip:ref:`~PyQt5.QtCore.QDateTime` does not account for leap seconds.

.. _qdatetime-remarks:

Remarks
-------

.. _qdatetime-no-year-0:

No Year 0
.........

There is no year 0. Dates in that year are considered invalid. The year -1 is the year "1 before Christ" or "1 before current era." The day before 1 January 1 CE is 31 December 1 BCE.

.. _qdatetime-range-of-valid-dates:

Range of Valid Dates
....................

The range of valid values able to be stored in :sip:ref:`~PyQt5.QtCore.QDateTime` is dependent on the internal storage implementation. :sip:ref:`~PyQt5.QtCore.QDateTime` is currently stored in a qint64 as a serial msecs value encoding the date and time. This restricts the date range to about +/- 292 million years, compared to the :sip:ref:`~PyQt5.QtCore.QDate` range of +/- 2 billion years. Care must be taken when creating a :sip:ref:`~PyQt5.QtCore.QDateTime` with extreme values that you do not overflow the storage. The exact range of supported values varies depending on the :sip:ref:`~PyQt5.QtCore.Qt.TimeSpec` and time zone.

.. _qdatetime-use-of-system-timezone:

Use of System Timezone
......................

:sip:ref:`~PyQt5.QtCore.QDateTime` uses the system's time zone information to determine the offset of local time from UTC. If the system is not configured correctly or not up-to-date, :sip:ref:`~PyQt5.QtCore.QDateTime` will give wrong results as well.

.. _qdatetime-daylight-saving-time-dst:

Daylight-Saving Time (DST)
..........................

:sip:ref:`~PyQt5.QtCore.QDateTime` takes into account the system's time zone information when dealing with DST. On modern Unix systems, this means it applies the correct historical DST data whenever possible. On Windows, where the system doesn't support historical DST data, historical accuracy is not maintained with respect to DST.

The range of valid dates taking DST into account is 1970-01-01 to the present, and rules are in place for handling DST correctly until 2037-12-31, but these could change. For dates falling outside that range, :sip:ref:`~PyQt5.QtCore.QDateTime` makes a *best guess* using the rules for year 1970 or 2037, but we can't guarantee accuracy. This means :sip:ref:`~PyQt5.QtCore.QDateTime` doesn't take into account changes in a locale's time zone before 1970, even if the system's time zone database supports that information.

:sip:ref:`~PyQt5.QtCore.QDateTime` takes into consideration the Standard Time to Daylight-Saving Time transition. For example if the transition is at 2am and the clock goes forward to 3am, then there is a "missing" hour from 02:00:00 to 02:59:59.999 which :sip:ref:`~PyQt5.QtCore.QDateTime` considers to be invalid. Any date maths performed will take this missing hour into account and return a valid result.

.. _qdatetime-offset-from-utc:

Offset From UTC
...............

A :sip:ref:`~PyQt5.QtCore.Qt.TimeSpec` of :sip:ref:`~PyQt5.QtCore.Qt.TimeSpec.OffsetFromUTC` is also supported. This allows you to define a :sip:ref:`~PyQt5.QtCore.QDateTime` relative to UTC at a fixed offset of a given number of seconds from UTC. For example, an offset of +3600 seconds is one hour ahead of UTC and is usually written in ISO standard notation as "UTC+01:00". Daylight-Saving Time never applies with this TimeSpec.

There is no explicit size restriction to the offset seconds, but there is an implicit limit imposed when using the :sip:ref:`~PyQt5.QtCore.QDateTime.toString` and :sip:ref:`~PyQt5.QtCore.QDateTime.fromString` methods which use a format of [+|-]hh:mm, effectively limiting the range to +/- 99 hours and 59 minutes and whole minutes only. Note that currently no time zone lies outside the range of +/- 14 hours.

.. _qdatetime-time-zone-support:

Time Zone Support
.................

A :sip:ref:`~PyQt5.QtCore.Qt.TimeSpec` of Qt::TimeZone is also supported in conjunction with the :sip:ref:`~PyQt5.QtCore.QTimeZone` class. This allows you to define a datetime in a named time zone adhering to a consistent set of daylight-saving transition rules. For example a time zone of "Europe/Berlin" will apply the daylight-saving rules as used in Germany since 1970. Note that the transition rules applied depend on the platform support. See the :sip:ref:`~PyQt5.QtCore.QTimeZone` documentation for more details.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QDate`, :sip:ref:`~PyQt5.QtCore.QTime`, :sip:ref:`~PyQt5.QtCore.QTimeZone`.
