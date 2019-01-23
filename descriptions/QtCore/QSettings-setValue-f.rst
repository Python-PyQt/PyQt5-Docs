.. sip:method-description::
    :status: todo
    :pysig: 9064598f6881fe97156ec2e9c47c55cf
    :realsig: (const QString&,const QVariant&)
    :digest: 51edf27d9acf05a22f43fb6725db8f0f

Sets the value of setting *key* to *value*. If the *key* already exists, the previous value is overwritten.

Note that the Windows registry and INI files use case-insensitive keys, whereas the CFPreferences API on `macOS <https://doc.qt.io/qt-5/qtwebengine-platform-notes.html#macos>`_ and iOS uses case-sensitive keys. To avoid portability problems, see the :ref:`qsettings-section-and-key-syntax` rules.

Example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_io_qsettings.py
    :lines: 257-262

.. seealso:: :sip:ref:`~PyQt5.QtCore.QSettings.value`, :sip:ref:`~PyQt5.QtCore.QSettings.remove`, :sip:ref:`~PyQt5.QtCore.QSettings.contains`.
