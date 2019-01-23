.. sip:method-description::
    :status: todo
    :pysig: c506ff134babdd6e68ab3e6350e95305
    :realsig: (bool)
    :digest: 8abaf853a1c5430a93f631861ba06542

Specifies whether mnemonics for menu items, labels, etc., should be honored or not. On Windows and X11, this feature is on by default; on `macOS <https://doc.qt.io/qt-5/qtwebengine-platform-notes.html#macos>`_, it is off. When this feature is off (that is, when *b* is false), :sip:ref:`~PyQt5.QtGui.QKeySequence.mnemonic` always returns an empty string.

**Note:** This function is not declared in any of Qt's header files. To use it in your application, declare the function prototype before calling it.

.. seealso:: :sip:ref:`~PyQt5.QtWidgets.QShortcut`.
