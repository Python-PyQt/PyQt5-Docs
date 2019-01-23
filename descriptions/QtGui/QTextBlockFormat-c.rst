.. sip:class-description::
    :status: todo
    :brief: Formatting information for blocks of text in a QTextDocument
    :digest: 1f45718908a45a30cf5ac533a063d1a8

The :sip:ref:`~PyQt5.QtGui.QTextBlockFormat` class provides formatting information for blocks of text in a :sip:ref:`~PyQt5.QtGui.QTextDocument`.

A document is composed of a list of blocks, represented by :sip:ref:`~PyQt5.QtGui.QTextBlock` objects. Each block can contain an item of some kind, such as a paragraph of text, a table, a list, or an image. Every block has an associated :sip:ref:`~PyQt5.QtGui.QTextBlockFormat` that specifies its characteristics.

To cater for left-to-right and right-to-left languages you can set a block's direction with setDirection(). Paragraph alignment is set with :sip:ref:`~PyQt5.QtGui.QTextBlockFormat.setAlignment`. Margins are controlled by :sip:ref:`~PyQt5.QtGui.QTextBlockFormat.setTopMargin`, :sip:ref:`~PyQt5.QtGui.QTextBlockFormat.setBottomMargin`, :sip:ref:`~PyQt5.QtGui.QTextBlockFormat.setLeftMargin`, :sip:ref:`~PyQt5.QtGui.QTextBlockFormat.setRightMargin`. Overall indentation is set with :sip:ref:`~PyQt5.QtGui.QTextBlockFormat.setIndent`, the indentation of the first line with :sip:ref:`~PyQt5.QtGui.QTextBlockFormat.setTextIndent`.

Line spacing is set with :sip:ref:`~PyQt5.QtGui.QTextBlockFormat.setLineHeight` and retrieved via :sip:ref:`~PyQt5.QtGui.QTextBlockFormat.lineHeight` and :sip:ref:`~PyQt5.QtGui.QTextBlockFormat.lineHeightType`. The types of line spacing available are in the :sip:ref:`~PyQt5.QtGui.QTextBlockFormat.LineHeightTypes.LineHeightTypes` enum.

Line breaking can be enabled and disabled with :sip:ref:`~PyQt5.QtGui.QTextBlockFormat.setNonBreakableLines`.

The brush used to paint the paragraph's background is set with :sip:ref:`~PyQt5.QtGui.QTextFormat.setBackground`, and other aspects of the text's appearance can be customized by using the :sip:ref:`~PyQt5.QtGui.QTextFormat.setProperty` function with the ``OutlinePen``, ``ForegroundBrush``, and ``BackgroundBrush`` :sip:ref:`~PyQt5.QtGui.QTextFormat.Property` values.

If a text block is part of a list, it can also have a list format that is accessible with the listFormat() function.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QTextBlock`, :sip:ref:`~PyQt5.QtGui.QTextCharFormat`.
