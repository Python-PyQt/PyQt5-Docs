.. sip:method-description::
    :status: todo
    :pysig: a71563477a277a464105dae1afb64ce8
    :realsig: (const QString&)
    :digest: 17287224c8bd292b36ed816ab6f518a2

Returns the shortcut key sequence for the mnemonic in *text*, or an empty key sequence if no mnemonics are found.

For example, mnemonic("E&xit") returns ``Qt::ALT+Qt::Key_X``, mnemonic("&Quit") returns ``ALT+Key_Q``, and mnemonic("Quit") returns an empty :sip:ref:`~PyQt5.QtGui.QKeySequence`.

We provide a list of common mnemonics in English. At the time of writing, Microsoft and Open Group do not appear to have issued equivalent recommendations for other languages.
