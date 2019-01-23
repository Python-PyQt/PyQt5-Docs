.. sip:method-description::
    :status: todo
    :pysig: 1faae77ca1cbd23ab6149553abae0885
    :realsig: (const QDate&) const
    :digest: 067aad06b488ebfd5e7f5c05a5c9d3e5

Returns the number of days from this date to *d* (which is negative if *d* is earlier than this date).

Returns 0 if either date is invalid.

Example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qdatetime.py
    :lines: 54-57

.. seealso:: :sip:ref:`~PyQt5.QtCore.QDate.addDays`.
