.. sip:class-description::
    :status: todo
    :brief: Event loop for Qt applications without UI
    :digest: aeac618719be2bfca5f421e49e1698ff

The :sip:ref:`~PyQt5.QtCore.QCoreApplication` class provides an event loop for Qt applications without UI.

This class is used by non-GUI applications to provide their event loop. For non-GUI application that uses Qt, there should be exactly one :sip:ref:`~PyQt5.QtCore.QCoreApplication` object. For GUI applications, see :sip:ref:`~PyQt5.QtGui.QGuiApplication`. For applications that use the Qt Widgets module, see QApplication.

:sip:ref:`~PyQt5.QtCore.QCoreApplication` contains the main event loop, where all events from the operating system (e.g., timer and network events) and other sources are processed and dispatched. It also handles the application's initialization and finalization, as well as system-wide and application-wide settings.

.. _qcoreapplication-the-event-loop-and-event-handling:

The Event Loop and Event Handling
---------------------------------

The event loop is started with a call to :sip:ref:`~PyQt5.QtCore.QCoreApplication.exec`. Long-running operations can call :sip:ref:`~PyQt5.QtCore.QCoreApplication.processEvents` to keep the application responsive.

In general, we recommend that you create a :sip:ref:`~PyQt5.QtCore.QCoreApplication`, :sip:ref:`~PyQt5.QtGui.QGuiApplication` or a QApplication object in your ``main()`` function as early as possible. :sip:ref:`~PyQt5.QtCore.QCoreApplication.exec` will not return until the event loop exits; e.g., when :sip:ref:`~PyQt5.QtCore.QCoreApplication.quit` is called.

Several static convenience functions are also provided. The :sip:ref:`~PyQt5.QtCore.QCoreApplication` object is available from :sip:ref:`~PyQt5.QtCore.QCoreApplication.instance`. Events can be sent with :sip:ref:`~PyQt5.QtCore.QCoreApplication.sendEvent` or posted to an event queue with :sip:ref:`~PyQt5.QtCore.QCoreApplication.postEvent`. Pending events can be removed with :sip:ref:`~PyQt5.QtCore.QCoreApplication.removePostedEvents` or dispatched with :sip:ref:`~PyQt5.QtCore.QCoreApplication.sendPostedEvents`.

The class provides a :sip:ref:`~PyQt5.QtCore.QCoreApplication.quit` slot and an :sip:ref:`~PyQt5.QtCore.QCoreApplication.aboutToQuit` signal.

.. _qcoreapplication-application-and-library-paths:

Application and Library Paths
-----------------------------

An application has an :sip:ref:`~PyQt5.QtCore.QCoreApplication.applicationDirPath` and an :sip:ref:`~PyQt5.QtCore.QCoreApplication.applicationFilePath`. Library paths (see :sip:ref:`~PyQt5.QtCore.QLibrary`) can be retrieved with :sip:ref:`~PyQt5.QtCore.QCoreApplication.libraryPaths` and manipulated by :sip:ref:`~PyQt5.QtCore.QCoreApplication.setLibraryPaths`, :sip:ref:`~PyQt5.QtCore.QCoreApplication.addLibraryPath`, and :sip:ref:`~PyQt5.QtCore.QCoreApplication.removeLibraryPath`.

.. _qcoreapplication-internationalization-and-translations:

Internationalization and Translations
-------------------------------------

Translation files can be added or removed using :sip:ref:`~PyQt5.QtCore.QCoreApplication.installTranslator` and :sip:ref:`~PyQt5.QtCore.QCoreApplication.removeTranslator`. Application strings can be translated using :sip:ref:`~PyQt5.QtCore.QCoreApplication.translate`. The :sip:ref:`~PyQt5.QtCore.QObject.tr` and QObject::trUtf8() functions are implemented in terms of :sip:ref:`~PyQt5.QtCore.QCoreApplication.translate`.

.. _qcoreapplication-accessing-command-line-arguments:

Accessing Command Line Arguments
--------------------------------

The command line arguments which are passed to :sip:ref:`~PyQt5.QtCore.QCoreApplication`'s constructor should be accessed using the :sip:ref:`~PyQt5.QtCore.QCoreApplication.arguments` function.

**Note:** :sip:ref:`~PyQt5.QtCore.QCoreApplication` removes option ``-qmljsdebugger="..."``. It parses the argument of ``qmljsdebugger``, and then removes this option plus its argument.

For more advanced command line option handling, create a :sip:ref:`~PyQt5.QtCore.QCommandLineParser`.

.. _qcoreapplication-locale-settings:

Locale Settings
---------------

On Unix/Linux Qt is configured to use the system locale settings by default. This can cause a conflict when using POSIX functions, for instance, when converting between data types such as floats and strings, since the notation may differ between locales. To get around this problem, call the POSIX function ``setlocale(LC_NUMERIC,"C")`` right after initializing QApplication, :sip:ref:`~PyQt5.QtGui.QGuiApplication` or :sip:ref:`~PyQt5.QtCore.QCoreApplication` to reset the locale that is used for number formatting to "C"-locale.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QGuiApplication`, :sip:ref:`~PyQt5.QtCore.QAbstractEventDispatcher`, :sip:ref:`~PyQt5.QtCore.QEventLoop`, `Semaphores Example <https://doc.qt.io/qt-5/qtcore-threads-semaphores-example.html>`_, `Wait Conditions Example <https://doc.qt.io/qt-5/qtcore-threads-waitconditions-example.html>`_.
