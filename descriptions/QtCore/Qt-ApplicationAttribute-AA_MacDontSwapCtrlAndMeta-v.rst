.. sip:enum-member-description::
    :status: todo
    :value: 7
    :digest: c17ce0baf56a4648350b91dcd7fb5e1d

On `macOS <https://doc.qt.io/qt-5/qtwebengine-platform-notes.html#macos>`_ by default, Qt swaps the Control and Meta (Command) keys (i.e., whenever Control is pressed, Qt sends Meta, and whenever Meta is pressed Control is sent). When this attribute is true, Qt will not do the flip. :sip:ref:`~PyQt5.QtGui.QKeySequence.StandardKey` will also flip accordingly (i.e., :sip:ref:`~PyQt5.QtGui.QKeySequence.StandardKey.Copy` will be Command+C on the keyboard regardless of the value set, though what is output for :sip:ref:`~PyQt5.QtGui.QKeySequence.toString` will be different).
