.. sip:class-description::
    :status: todo
    :brief: Date functions
    :digest: c2c1dfb2261311f1616c8af8cc1c6b23

The :sip:ref:`~PyQt5.QtCore.QDate` class provides date functions.

A :sip:ref:`~PyQt5.QtCore.QDate` object encodes a calendar date, i.e. year, month, and day numbers, in the proleptic Gregorian calendar by default. It can read the current date from the system clock. It provides functions for comparing dates, and for manipulating dates. For example, it is possible to add and subtract days, months, and years to dates.

A :sip:ref:`~PyQt5.QtCore.QDate` object is typically created by giving the year, month, and day numbers explicitly. Note that :sip:ref:`~PyQt5.QtCore.QDate` interprets two digit years as presented, i.e., as years 0 through 99, without adding any offset. A :sip:ref:`~PyQt5.QtCore.QDate` can also be constructed with the static function :sip:ref:`~PyQt5.QtCore.QDate.currentDate`, which creates a :sip:ref:`~PyQt5.QtCore.QDate` object containing the system clock's date. An explicit date can also be set using :sip:ref:`~PyQt5.QtCore.QDate.setDate`. The :sip:ref:`~PyQt5.QtCore.QDate.fromString` function returns a :sip:ref:`~PyQt5.QtCore.QDate` given a string and a date format which is used to interpret the date within the string.

The :sip:ref:`~PyQt5.QtCore.QDate.year`, :sip:ref:`~PyQt5.QtCore.QDate.month`, and :sip:ref:`~PyQt5.QtCore.QDate.day` functions provide access to the year, month, and day numbers. Also, :sip:ref:`~PyQt5.QtCore.QDate.dayOfWeek` and :sip:ref:`~PyQt5.QtCore.QDate.dayOfYear` functions are provided. The same information is provided in textual format by the :sip:ref:`~PyQt5.QtCore.QDate.toString`, :sip:ref:`~PyQt5.QtCore.QDate.shortDayName`, :sip:ref:`~PyQt5.QtCore.QDate.longDayName`, :sip:ref:`~PyQt5.QtCore.QDate.shortMonthName`, and :sip:ref:`~PyQt5.QtCore.QDate.longMonthName` functions.

:sip:ref:`~PyQt5.QtCore.QDate` provides a full set of operators to compare two :sip:ref:`~PyQt5.QtCore.QDate` objects where smaller means earlier, and larger means later.

You can increment (or decrement) a date by a given number of days using :sip:ref:`~PyQt5.QtCore.QDate.addDays`. Similarly you can use :sip:ref:`~PyQt5.QtCore.QDate.addMonths` and :sip:ref:`~PyQt5.QtCore.QDate.addYears`. The :sip:ref:`~PyQt5.QtCore.QDate.daysTo` function returns the number of days between two dates.

The :sip:ref:`~PyQt5.QtCore.QDate.daysInMonth` and :sip:ref:`~PyQt5.QtCore.QDate.daysInYear` functions return how many days there are in this date's month and year, respectively. The :sip:ref:`~PyQt5.QtCore.QDate.isLeapYear` function indicates whether a date is in a leap year.

.. _qdate-remarks:

Remarks
-------

.. _qdate-no-year-0:

No Year 0
.........

There is no year 0. Dates in that year are considered invalid. The year -1 is the year "1 before Christ" or "1 before current era." The day before 1 January 1 CE, :sip:ref:`~PyQt5.QtCore.QDate`\ (1, 1, 1), is 31 December 1 BCE, :sip:ref:`~PyQt5.QtCore.QDate`\ (-1, 12, 31).

.. _qdate-range-of-valid-dates:

Range of Valid Dates
....................

Dates are stored internally as a Julian Day number, an integer count of every day in a contiguous range, with 24 November 4714 BCE in the Gregorian calendar being Julian Day 0 (1 January 4713 BCE in the Julian calendar). As well as being an efficient and accurate way of storing an absolute date, it is suitable for converting a Date into other calendar systems such as Hebrew, Islamic or Chinese. The Julian Day number can be obtained using :sip:ref:`~PyQt5.QtCore.QDate.toJulianDay` and can be set using :sip:ref:`~PyQt5.QtCore.QDate.fromJulianDay`.

The range of dates able to be stored by :sip:ref:`~PyQt5.QtCore.QDate` as a Julian Day number is for technical reasons limited to between -784350574879 and 784354017364, which means from before 2 billion BCE to after 2 billion CE.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QTime`, :sip:ref:`~PyQt5.QtCore.QDateTime`.
