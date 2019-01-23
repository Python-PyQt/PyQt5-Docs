.. sip:method-description::
    :status: todo
    :pysig: e7c5b531a652dfacc335575c2b9c6467
    :realsig: (int*,QTextLine::Edge) const
    :digest: 50e7ba620b7bfaee47a7d7c22677cc10

Converts the cursor position *cursorPos* to the corresponding x position inside the line, taking account of the *edge*.

If *cursorPos* is not a valid cursor position, the nearest valid cursor position will be used instead, and *cursorPos* will be modified to point to this valid cursor position.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QTextLine.xToCursor`.
