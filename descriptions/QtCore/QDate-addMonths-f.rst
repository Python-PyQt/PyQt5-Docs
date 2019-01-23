.. sip:method-description::
    :status: todo
    :pysig: 5a52f43801c37c10615a8f7a1bc18c4c
    :realsig: (int) const
    :digest: ed01fd16d44eafebbe5ffee3a1585e19

Returns a :sip:ref:`~PyQt5.QtCore.QDate` object containing a date *nmonths* later than the date of this object (or earlier if *nmonths* is negative).

**Note:** If the ending day/month combination does not exist in the resulting month/year, this function will return a date that is the latest valid date.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QDate.addDays`, :sip:ref:`~PyQt5.QtCore.QDate.addYears`.
