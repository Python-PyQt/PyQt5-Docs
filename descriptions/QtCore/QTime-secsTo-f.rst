.. sip:method-description::
    :status: todo
    :pysig: 4c1b4ac927cbba1cbd275966b9e0aea1
    :realsig: (const QTime&) const
    :digest: c5941102eeb997d3643d0cb570b0679c

Returns the number of seconds from this time to *t*. If *t* is earlier than this time, the number of seconds returned is negative.

Because :sip:ref:`~PyQt5.QtCore.QTime` measures time within a day and there are 86400 seconds in a day, the result is always between -86400 and 86400.

does not take into account any milliseconds.

Returns 0 if either time is invalid.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QTime.addSecs`, :sip:ref:`~PyQt5.QtCore.QDateTime.secsTo`.
