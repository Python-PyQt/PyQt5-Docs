.. sip:method-description::
    :status: todo
    :pysig: 883579c2ad1a92ea9bbe04c13915d560
    :realsig: (int,int,int)
    :digest: ec3c660635af022aa8ea17811792eb7d

Constructs a date with year *y*, month *m* and day *d*.

If the specified date is invalid, the date is not set and :sip:ref:`~PyQt5.QtCore.QDate.isValid` returns ``false``.

**Warning:** Years 1 to 99 are interpreted as is. Year 0 is invalid.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QDate.isValid`.
