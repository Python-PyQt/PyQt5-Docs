.. sip:method-description::
    :status: todo
    :pysig: 271114a2a22d3ca565d36181042b8525
    :realsig: (const QRegExp&,const QTextCursor&,QTextDocument::FindFlags) const
    :digest: 5257de7fcbf2ab0ea26f3ddb47a50b5b

This is an overloaded function.

Finds the next occurrence that matches the given regular expression, *expr*, within the same paragraph in the document.

The search starts at the position of the given from *cursor*, and proceeds forwards through the document unless specified otherwise in the search options. The *options* control the type of search performed. The :sip:ref:`~PyQt5.QtGui.QTextDocument.FindFlag.FindCaseSensitively` option is ignored for this overload, use :sip:ref:`~PyQt5.QtCore.QRegExp.caseSensitivity` instead.

Returns a cursor with the match selected if a match was found; otherwise returns a null cursor.

If the given *cursor* has a selection, the search begins after the selection; otherwise it begins at the cursor's position.

By default the search is case insensitive, and can match text anywhere in the document.
