.. sip:method-description::
    :status: todo
    :pysig: 61569f2965b7a369eb10b6d75d410d11
    :realsig: (int*) const
    :digest: e73b0b11ee2eef752271dc50bda7fbf9

Returns the week number (1 to 53), and stores the year in \*\ *yearNumber* unless *yearNumber* is null (the default).

Returns 0 if the date is invalid.

In accordance with ISO 8601, weeks start on Monday and the first Thursday of a year is always in week 1 of that year. Most years have 52 weeks, but some have 53.

\*\ *yearNumber* is not always the same as :sip:ref:`~PyQt5.QtCore.QDate.year`. For example, 1 January 2000 has week number 52 in the year 1999, and 31 December 2002 has week number 1 in the year 2003.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QDate.isValid`.
