.. sip:method-description::
    :status: todo
    :pysig: 9d2496c01394f04863ec354dfad3b4be
    :realsig: (const QString&) const
    :digest: 5fc1360d94d347efec3fab73900ed6ab

Returns ``true`` if there exists a setting called *key*; returns false otherwise.

If a group is set using :sip:ref:`~PyQt5.QtCore.QSettings.beginGroup`, *key* is taken to be relative to that group.

Note that the Windows registry and INI files use case-insensitive keys, whereas the CFPreferences API on `macOS <https://doc.qt.io/qt-5/qtwebengine-platform-notes.html#macos>`_ and iOS uses case-sensitive keys. To avoid portability problems, see the :ref:`qsettings-section-and-key-syntax` rules.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QSettings.value`, :sip:ref:`~PyQt5.QtCore.QSettings.setValue`.
