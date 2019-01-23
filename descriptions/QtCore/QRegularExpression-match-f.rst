.. sip:method-description::
    :status: todo
    :pysig: 8f9ced69fd811a02b640e8e1dbc30bfc
    :realsig: (const QString&,int,QRegularExpression::MatchType,QRegularExpression::MatchOptions) const
    :digest: 8dd5e2fafb4e8f61211892de4e9c28cc

Attempts to match the regular expression against the given *subject* string, starting at the position *offset* inside the subject, using a match of type *matchType* and honoring the given *matchOptions*.

The returned :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatch` object contains the results of the match.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QRegularExpressionMatch`, :ref:`normal matching<qregularexpression-normal-matching>`.
