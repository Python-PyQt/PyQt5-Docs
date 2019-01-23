.. sip:method-description::
    :status: todo
    :pysig: 5a52f43801c37c10615a8f7a1bc18c4c
    :realsig: (int) const
    :digest: fb31382cfa140c97f24b67cce2b4b39b

Returns a :sip:ref:`~PyQt5.QtCore.QDate` object containing a date *nyears* later than the date of this object (or earlier if *nyears* is negative).

**Note:** If the ending day/month combination does not exist in the resulting year (i.e., if the date was Feb 29 and the final year is not a leap year), this function will return a date that is the latest valid date (that is, Feb 28).

.. seealso:: :sip:ref:`~PyQt5.QtCore.QDate.addDays`, :sip:ref:`~PyQt5.QtCore.QDate.addMonths`.
