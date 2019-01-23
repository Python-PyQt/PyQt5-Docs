.. sip:method-description::
    :status: todo
    :pysig: 7becb2df7b92d8a97ec9b703f52858db
    :realsig: (const QRegExp&,int,QTextDocument::FindFlags) const
    :digest: a257c2a1cdb4f65ab31f8573b8bfe251

This is an overloaded function.

Finds the next occurrence that matches the given regular expression, *expr*, within the same paragraph in the document.

The search starts at the given *from* position, and proceeds forwards through the document unless specified otherwise in the search options. The *options* control the type of search performed. The :sip:ref:`~PyQt5.QtGui.QTextDocument.FindFlag.FindCaseSensitively` option is ignored for this overload, use :sip:ref:`~PyQt5.QtCore.QRegExp.caseSensitivity` instead.

Returns a cursor with the match selected if a match was found; otherwise returns a null cursor.

If the *from* position is 0 (the default) the search begins from the beginning of the document; otherwise it begins at the specified position.
