.. sip:method-description::
    :status: todo
    :pysig: 58c24d78b59adbc8978a79fd1fee9b6c
    :realsig: (int) const
    :digest: 7dde240ec885c1816c8e2dcc21e081ac

Returns a :sip:ref:`~PyQt5.QtCore.QTime` object containing a time *s* seconds later than the time of this object (or earlier if *s* is negative).

Note that the time will wrap if it passes midnight.

Returns a null time if this time is invalid.

Example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qdatetime.py
    :lines: 91-96

.. seealso:: :sip:ref:`~PyQt5.QtCore.QTime.addMSecs`, :sip:ref:`~PyQt5.QtCore.QTime.secsTo`, :sip:ref:`~PyQt5.QtCore.QDateTime.addSecs`.
