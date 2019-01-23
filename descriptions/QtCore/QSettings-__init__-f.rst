.. sip:method-description::
    :status: todo
    :pysig: f3c1ea8cdc226f1c6d1536b6891b19f7
    :realsig: (QObject*)
    :digest: 3824917d05ade152a981e8f2462e6720

Constructs a :sip:ref:`~PyQt5.QtCore.QSettings` object for accessing settings of the application and organization set previously with a call to :sip:ref:`~PyQt5.QtCore.QCoreApplication.setOrganizationName`, :sip:ref:`~PyQt5.QtCore.QCoreApplication.setOrganizationDomain`, and :sip:ref:`~PyQt5.QtCore.QCoreApplication.setApplicationName`.

The scope is QSettings::UserScope and the format is :sip:ref:`~PyQt5.QtCore.QSettings.defaultFormat` (QSettings::NativeFormat by default). Use :sip:ref:`~PyQt5.QtCore.QSettings.setDefaultFormat` before calling this constructor to change the default format used by this constructor.

The code

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_io_qsettings.py
    :lines: 121-121

is equivalent to

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_io_qsettings.py
    :lines: 126-128

If :sip:ref:`~PyQt5.QtCore.QCoreApplication.setOrganizationName` and :sip:ref:`~PyQt5.QtCore.QCoreApplication.setApplicationName` has not been previously called, the :sip:ref:`~PyQt5.QtCore.QSettings` object will not be able to read or write any settings, and :sip:ref:`~PyQt5.QtCore.QSettings.status` will return :sip:ref:`~PyQt5.QtCore.QSettings.Status.AccessError`.

On `macOS <https://doc.qt.io/qt-5/qtwebengine-platform-notes.html#macos>`_ and iOS, if both a name and an Internet domain are specified for the organization, the domain is preferred over the name. On other platforms, the name is preferred over the domain.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QCoreApplication.setOrganizationName`, :sip:ref:`~PyQt5.QtCore.QCoreApplication.setOrganizationDomain`, :sip:ref:`~PyQt5.QtCore.QCoreApplication.setApplicationName`, :sip:ref:`~PyQt5.QtCore.QSettings.setDefaultFormat`.
