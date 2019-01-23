.. sip:method-description::
    :status: todo
    :pysig: 45f8a4a84005a4575b19f664801273e8
    :realsig: (QTextCursor*)
    :digest: 4ff278b7d3adcd5b7a5af65497839406

Undoes the last editing operation on the document if undo is available. The provided *cursor* is positioned at the end of the location where the edition operation was undone.

See the Qt Undo Framework documentation for details.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QTextDocument.undoAvailable`, :sip:ref:`~PyQt5.QtGui.QTextDocument.isUndoRedoEnabled`.
