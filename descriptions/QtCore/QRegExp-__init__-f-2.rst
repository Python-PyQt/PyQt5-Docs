.. sip:method-description::
    :status: todo
    :pysig: 13df32bca2aa149b056842403ea2ffff
    :realsig: (const QString&,Qt::CaseSensitivity,QRegExp::PatternSyntax)
    :digest: 402c77aa41b3409753b28755171242de

Constructs a regular expression object for the given *pattern* string. The pattern must be given using wildcard notation if *syntax* is :sip:ref:`~PyQt5.QtCore.QRegExp.PatternSyntax.Wildcard`; the default is :sip:ref:`~PyQt5.QtCore.QRegExp.PatternSyntax.RegExp`. The pattern is case sensitive, unless *cs* is :sip:ref:`~PyQt5.QtCore.Qt.CaseSensitivity.CaseInsensitive`. Matching is greedy (maximal), but can be changed by calling :sip:ref:`~PyQt5.QtCore.QRegExp.setMinimal`.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QRegExp.setPattern`, :sip:ref:`~PyQt5.QtCore.QRegExp.setCaseSensitivity`, :sip:ref:`~PyQt5.QtCore.QRegExp.setPatternSyntax`.
