.. sip:class-description::
    :status: todo
    :brief: Represents a category, or 'area' in the logging infrastructure
    :digest: f159e280326be1f8fbb6221fe6d49fa6

The :sip:ref:`~PyQt5.QtCore.QLoggingCategory` class represents a category, or 'area' in the logging infrastructure.

:sip:ref:`~PyQt5.QtCore.QLoggingCategory` represents a certain logging category - identified by a string - at runtime. A category can be configured to enable or disable logging of messages per message type. Whether a message type is enabled or not can be checked with the :sip:ref:`~PyQt5.QtCore.QLoggingCategory.isDebugEnabled`, :sip:ref:`~PyQt5.QtCore.QLoggingCategory.isInfoEnabled`, :sip:ref:`~PyQt5.QtCore.QLoggingCategory.isWarningEnabled`, and :sip:ref:`~PyQt5.QtCore.QLoggingCategory.isCriticalEnabled` methods.

All objects are meant to be configured by a common registry (see also :ref:`qloggingcategory-configuring-categories`). Different objects can also represent the same category. It is therefore not recommended to export objects across module boundaries, nor to manipulate the objects directly, nor to inherit from :sip:ref:`~PyQt5.QtCore.QLoggingCategory`.

.. _qloggingcategory-creating-category-objects:

Creating Category Objects
-------------------------

The Q_DECLARE_LOGGING_CATEGORY() and Q_LOGGING_CATEGORY() macros conveniently declare and create :sip:ref:`~PyQt5.QtCore.QLoggingCategory` objects:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-qloggingcategory-main.py

**Note:** Category names are free text. However, to allow easy configuration of the categories using :ref:`qloggingcategory-logging-rules` the names should follow some rules:

* Use letters and numbers only.

* Further structure categories into common areas by using dots.

* Avoid the category names ``debug``, ``info``, ``warning``, and ``critical``.

* Category names starting with ``qt`` are reserved for Qt modules.

:sip:ref:`~PyQt5.QtCore.QLoggingCategory` objects implicitly defined by Q_LOGGING_CATEGORY() are created on first use in a thread-safe manner.

.. _qloggingcategory-checking-category-configuration:

Checking Category Configuration
-------------------------------

:sip:ref:`~PyQt5.QtCore.QLoggingCategory` provides :sip:ref:`~PyQt5.QtCore.QLoggingCategory.isDebugEnabled`, :sip:ref:`~PyQt5.QtCore.QLoggingCategory.isInfoEnabled`, :sip:ref:`~PyQt5.QtCore.QLoggingCategory.isWarningEnabled`, :sip:ref:`~PyQt5.QtCore.QLoggingCategory.isCriticalEnabled`, as well as :sip:ref:`~PyQt5.QtCore.QLoggingCategory.isEnabled` to check whether messages for the given message type should be logged.

**Note:** The qCDebug(), qCWarning(), qCCritical() macros prevent arguments from being evaluated if the respective message types are not enabled for the category, so explicit checking is not needed:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-qloggingcategory-main.py

.. _qloggingcategory-default-category-configuration:

Default Category Configuration
------------------------------

Both the :sip:ref:`~PyQt5.QtCore.QLoggingCategory` constructor and the Q_LOGGING_CATEGORY() macro accept an optional :sip:ref:`~PyQt5.QtCore.QtMsgType` argument, which disables all message types with a lower severity. That is, a category declared with

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-qloggingcategory-main.py

will log messages of type ``QtWarningMsg``, ``QtCriticalMsg``, ``QtFatalMsg``, but will ignore messages of type ``QtDebugMsg`` and ``QtInfoMsg``.

If no argument is passed, all messages will be logged.

.. _qloggingcategory-configuring-categories:

Configuring Categories
----------------------

The default configuration of categories can be overridden either by setting logging rules, or by installing a custom filter.

.. _qloggingcategory-logging-rules:

Logging Rules
.............

Logging rules allow logging for categories to be enabled or disabled in a flexible way. Rules are specified in text, where every line must have the format

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_io_qloggingcategory.py
    :lines: 43-43

``<category>`` is the name of the category, potentially with ``\*`` as a wildcard symbol as the first or last character (or at both positions). The optional ``<type>`` must be either ``debug``, ``info``, ``warning``, or ``critical``. Lines that do not fit this scheme are ignored.

Rules are evaluated in text order, from first to last. That is, if two rules apply to a category/type, the rule that comes later is applied.

Rules can be set via :sip:ref:`~PyQt5.QtCore.QLoggingCategory.setFilterRules`:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_io_qloggingcategory.py
    :lines: 47-48

Since Qt 5.3, logging rules are also automatically loaded from the ``[Rules]`` section of a logging configuration file. Such configuration files are looked up in the QtProject configuration directory, or explicitly set in a ``QT_LOGGING_CONF`` environment variable:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_io_qloggingcategory.py
    :lines: 52-54

Since Qt 5.3, logging rules can also be specified in a ``QT_LOGGING_RULES`` environment variable. And since Qt 5.6, multiple rules can also be separated by semicolons:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_io_qloggingcategory.py
    :lines: 58-58

Rules set by :sip:ref:`~PyQt5.QtCore.QLoggingCategory.setFilterRules` take precedence over rules specified in the QtProject configuration directory, and can, in turn, be overwritten by rules from the configuration file specified by ``QT_LOGGING_CONF``, and rules set by ``QT_LOGGING_RULES``.

Order of evaluation:

* [\ :sip:ref:`~PyQt5.QtCore.QLibraryInfo.LibraryLocation.DataPath`]/qtlogging.ini

* QtProject/qtlogging.ini

* :sip:ref:`~PyQt5.QtCore.QLoggingCategory.setFilterRules`

* ``QT_LOGGING_CONF``

* ``QT_LOGGING_RULES``

The ``QtProject/qtlogging.ini`` file is looked up in all directories returned by :sip:ref:`~PyQt5.QtCore.QStandardPaths.StandardLocation.GenericConfigLocation`, e.g.

* on `macOS <https://doc.qt.io/qt-5/qtwebengine-platform-notes.html#macos>`_ and iOS: ``~/Library/Preferences``

* on Unix: ``~/.config``, ``/etc/xdg``

* on Windows: ``%LOCALAPPDATA%``, ``%ProgramData%``, :sip:ref:`~PyQt5.QtCore.QCoreApplication.applicationDirPath`, :sip:ref:`~PyQt5.QtCore.QCoreApplication.applicationDirPath` + ``"/data"``

Set the ``QT_LOGGING_DEBUG`` environment variable to see from where logging rules are loaded.

.. _qloggingcategory-installing-a-custom-filter:

Installing a Custom Filter
..........................

As a lower-level alternative to the text rules, you can also implement a custom filter via installFilter(). All filter rules are ignored in this case.

.. _qloggingcategory-printing-the-category:

Printing the Category
---------------------

Use the ``%{category}`` placeholder to print the category in the default message handler:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-qloggingcategory-main.py
