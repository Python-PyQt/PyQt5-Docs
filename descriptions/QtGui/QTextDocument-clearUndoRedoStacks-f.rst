.. sip:method-description::
    :status: todo
    :pysig: f709bf85e42555d214b664e9ee1b98ea
    :realsig: (QTextDocument::Stacks)
    :digest: c3f2335363ae78d4b18084ddb6ee5fda

Clears the stacks specified by *stacksToClear*.

This method clears any commands on the undo stack, the redo stack, or both (the default). If commands are cleared, the appropriate signals are emitted, :sip:ref:`~PyQt5.QtGui.QTextDocument.undoAvailable` or :sip:ref:`~PyQt5.QtGui.QTextDocument.redoAvailable`.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QTextDocument.undoAvailable`, :sip:ref:`~PyQt5.QtGui.QTextDocument.redoAvailable`.
