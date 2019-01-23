.. sip:method-description::
    :status: todo
    :pysig: 8ab4347988e1e2d35a895e2742a76cae
    :realsig: (const QTextCharFormat&)
    :digest: f980df6d577b740f87518f5d3d8ab47a

Sets the cell's character format to *format*. This can for example be used to change the background color of the entire cell:

:sip:ref:`~PyQt5.QtGui.QTextTableCell` cell = table->cellAt(2, 3); :sip:ref:`~PyQt5.QtGui.QTextCharFormat` format = cell.\ :sip:ref:`~PyQt5.QtGui.QTextTableCell.format`; format.setBackground(\ :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor.blue`); cell.(format);

Note that the cell's row or column span cannot be changed through this function. You have to use :sip:ref:`~PyQt5.QtGui.QTextTable.mergeCells` and :sip:ref:`~PyQt5.QtGui.QTextTable.splitCell` instead.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QTextTableCell.format`.
