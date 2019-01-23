.. sip:method-description::
    :status: todo
    :pysig: e45a1617b143cf5f1139151c290be375
    :realsig: (const QString&,int,QRegularExpression::MatchType,QRegularExpression::MatchOptions) const
    :digest: 23fb852a7bfdf03afa00092868c1f1e8

Attempts to perform a global match of the regular expression against the given *subject* string, starting at the position *offset* inside the subject, using a match of type *matchType* and honoring the given *matchOptions*.

The returned :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatchIterator` is positioned before the first match result (if any).

.. seealso:: :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatchIterator`, :ref:`global matching<qregularexpression-global-matching>`.
