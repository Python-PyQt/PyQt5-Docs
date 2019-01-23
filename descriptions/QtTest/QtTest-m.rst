.. sip:module-description::
    :status:    done
    :brief:     Support for unit testing of GUI applications

The :sip:ref:`~PyQt5.QtTest` module contains functions that enable unit testing
of PyQt5 applications.  (PyQt5 does not implement the complete Qt unit test
framework.  Instead it assumes that the standard Python unit test framework
will be used and implements those functions that simulate a user interacting
with a GUI.)  In addition the :sip:ref:`~PyQt5.QtTest.QSignalSpy` class
provides easy introspection of Qt's signals and slots.
