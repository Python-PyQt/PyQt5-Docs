.. sip:class-description::
    :status: todo
    :brief: Information about the operating system version
    :digest: 6e7bee1d9b825f5c71a6b08b6cc2df2c

The :sip:ref:`~PyQt5.QtCore.QOperatingSystemVersion` class provides information about the operating system version.

Unlike other version functions in :sip:ref:`~PyQt5.QtCore.QSysInfo`, :sip:ref:`~PyQt5.QtCore.QOperatingSystemVersion` provides access to the full version number that *developers* typically use to vary behavior or determine whether to enable APIs or features based on the operating system version (as opposed to the kernel version number or marketing version).

This class is also a complete replacement for QSysInfo::macVersion and QSysInfo::windowsVersion, additionally providing access to the third (micro) version number component.

Presently, Android, Apple Platforms (iOS, `macOS <https://doc.qt.io/qt-5/qtwebengine-platform-notes.html#macos>`_, tvOS, and watchOS), and Windows are supported.

The *majorVersion()*, *minorVersion()*, and *microVersion()* functions return the parts of the operating system version number based on:

+-----------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Platforms       | Value                                                                                                                                                                                                                                                                                                                 |
+=================+=======================================================================================================================================================================================================================================================================================================================+
| Android         | result of parsing android.os.Build.VERSION.RELEASE using QVersionNumber, with a fallback to android.os.Build.VERSION.SDK_INT to determine the major and minor version component if the former fails                                                                                                                   |
+-----------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Apple Platforms | :sip:ref:`~PyQt5.QtCore.QOperatingSystemVersion.majorVersion`, :sip:ref:`~PyQt5.QtCore.QOperatingSystemVersion.minorVersion`, and patchVersion from NSProcessInfo.operatingSystemVersion                                                                                                                              |
+-----------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Windows         | dwMajorVersion, dwMinorVersion, and dwBuildNumber from RtlGetVersion - note that this function ALWAYS return the version number of the underlying operating system, as opposed to the shim underneath GetVersionEx that hides the real version number if the application is not manifested for that version of the OS |
+-----------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Because :sip:ref:`~PyQt5.QtCore.QOperatingSystemVersion` stores both a version number and an OS type, the OS type can be taken into account when performing comparisons. For example, on a `macOS <https://doc.qt.io/qt-5/qtwebengine-platform-notes.html#macos>`_ system running `macOS <https://doc.qt.io/qt-5/qtwebengine-platform-notes.html#macos>`_ Sierra (v10.12), the following expression will return ``false`` even though the major version number component of the object on the left hand side of the expression (10) is greater than that of the object on the right (9):

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_global_qoperatingsystemversion.py
    :lines: 43-43

This allows expressions for multiple operating systems to be joined with a logical OR operator and still work as expected. For example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_global_qoperatingsystemversion.py
    :lines: 47-51

A more naive comparison algorithm might incorrectly return true on all versions of `macOS <https://doc.qt.io/qt-5/qtwebengine-platform-notes.html#macos>`_, including Mac OS 9. This behavior is achieved by overloading the comparison operators to return ``false`` whenever the OS types of the :sip:ref:`~PyQt5.QtCore.QOperatingSystemVersion` instances being compared do not match. Be aware that due to this it can be the case ``x`` >= y and ``x`` < y are BOTH ``false`` for the same instances of ``x`` and ``y``.
