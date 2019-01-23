.. sip:method-description::
    :status: todo
    :pysig: 9d1cf9d086563284e841b724995588ae
    :realsig: () const
    :digest: c2ec9a962f8b91c13c521c243ed63a84

This function returns a block to test for the end of the document while iterating over it.

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-textdocumentendsnippet.py
    :lines: 63-64

The block returned is invalid and represents the block after the last block in the document. You can use :sip:ref:`~PyQt5.QtGui.QTextDocument.lastBlock` to retrieve the last valid block of the document.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QTextDocument.lastBlock`.
