.. sip:method-description::
    :status: todo
    :pysig: 8ab4347988e1e2d35a895e2742a76cae
    :realsig: (const QTextCharFormat&)
    :digest: e8f272b6e60e77df6865a43ac7c8a00b

Merges the cursor's current character format with the properties described by format *modifier*. If the cursor has a selection, this function applies all the properties set in *modifier* to all the character formats that are part of the selection.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QTextCursor.hasSelection`, :sip:ref:`~PyQt5.QtGui.QTextCursor.setCharFormat`.
