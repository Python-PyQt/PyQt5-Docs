.. sip:class-description::
    :status: todo
    :brief: QTextBlock::iterator class provides an iterator for reading the contents of a QTextBlock
    :digest: a4f8bf17467770eca6d5ac0199125589

The :sip:ref:`~PyQt5.QtGui.QTextBlock.iterator` class provides an iterator for reading the contents of a :sip:ref:`~PyQt5.QtGui.QTextBlock`.

A block consists of a sequence of text fragments. This class provides a way to iterate over these, and read their contents. It does not provide a way to modify the internal structure or contents of the block.

An iterator can be constructed and used to access the fragments within a text block in the following way:

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-textblock-fragments-xmlwriter.py
    :lines: 101-106

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-textblock-fragments-xmlwriter.py
    :lines: 119-119

.. seealso:: :sip:ref:`~PyQt5.QtGui.QTextFragment`.
