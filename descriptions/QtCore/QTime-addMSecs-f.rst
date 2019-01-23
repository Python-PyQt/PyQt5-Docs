.. sip:method-description::
    :status: todo
    :pysig: 58c24d78b59adbc8978a79fd1fee9b6c
    :realsig: (int) const
    :digest: 01ae7fee32b25027b48af0e5d683c196

Returns a :sip:ref:`~PyQt5.QtCore.QTime` object containing a time *ms* milliseconds later than the time of this object (or earlier if *ms* is negative).

Note that the time will wrap if it passes midnight. See :sip:ref:`~PyQt5.QtCore.QTime.addSecs` for an example.

Returns a null time if this time is invalid.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QTime.addSecs`, :sip:ref:`~PyQt5.QtCore.QTime.msecsTo`, :sip:ref:`~PyQt5.QtCore.QDateTime.addMSecs`.
