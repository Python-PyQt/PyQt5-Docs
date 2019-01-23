.. sip:method-description::
    :status: todo
    :pysig: bf9b7b002c967dddb201ffbc23914018
    :realsig: (QTextBlockUserData*)
    :digest: cda18909f33beff5517c741d86af6095

Attaches the given *data* to the current text block. The ownership is passed to the underlying text document, i.e. the provided :sip:ref:`~PyQt5.QtGui.QTextBlockUserData` object will be deleted if the corresponding text block gets deleted.

:sip:ref:`~PyQt5.QtGui.QTextBlockUserData` can be used to store custom settings. In the case of syntax highlighting, it is in particular interesting as cache storage for information that you may figure out while parsing the paragraph's text.

For example while parsing the text, you can keep track of parenthesis characters that you encounter ('{[(' and the like), and store their relative position and the actual QChar in a simple class derived from :sip:ref:`~PyQt5.QtGui.QTextBlockUserData`:

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-code-src_gui_text_qsyntaxhighlighter.py
    :lines: 109-118

During cursor navigation in the associated editor, you can ask the current :sip:ref:`~PyQt5.QtGui.QTextBlock` (retrieved using the :sip:ref:`~PyQt5.QtGui.QTextCursor.block` function) if it has a user data object set and cast it to your ``BlockData`` object. Then you can check if the current cursor position matches with a previously recorded parenthesis position, and, depending on the type of parenthesis (opening or closing), find the next opening or closing parenthesis on the same level.

In this way you can do a visual parenthesis matching and highlight from the current cursor position to the matching parenthesis. That makes it easier to spot a missing parenthesis in your code and to find where a corresponding opening/closing parenthesis is when editing parenthesis intensive code.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QSyntaxHighlighter.currentBlockUserData`, :sip:ref:`~PyQt5.QtGui.QTextBlock.setUserData`.
