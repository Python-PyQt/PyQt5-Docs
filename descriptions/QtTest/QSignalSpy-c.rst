.. sip:class-description::
    :status: todo
    :brief: Enables introspection of signal emission
    :digest: a89fa3756fd2f01fbfd294cafa5eedde

The :sip:ref:`~PyQt5.QtTest.QSignalSpy` class enables introspection of signal emission.

:sip:ref:`~PyQt5.QtTest.QSignalSpy` can connect to any signal of any object and records its emission. :sip:ref:`~PyQt5.QtTest.QSignalSpy` itself is a list of :sip:ref:`~PyQt5.QtCore.QVariant` lists. Each emission of the signal will append one item to the list, containing the arguments of the signal.

The following example records all signal emissions for the ``clicked()`` signal of a QCheckBox:

.. literalinclude:: ../../../snippets/qtbase-src-testlib-doc-snippets-code-doc_src_qsignalspy.py
    :lines: 54-63

``spy.takeFirst()`` returns the arguments for the first emitted signal, as a list of :sip:ref:`~PyQt5.QtCore.QVariant` objects. The ``clicked()`` signal has a single bool argument, which is stored as the first entry in the list of arguments.

The example below catches a signal from a custom object:

.. literalinclude:: ../../../snippets/qtbase-src-testlib-doc-snippets-code-doc_src_qsignalspy.py
    :lines: 68-75

**Note:** Non-standard data types need to be registered, using the qRegisterMetaType() function, before you can create a :sip:ref:`~PyQt5.QtTest.QSignalSpy`. For example:

.. literalinclude:: ../../../snippets/qtbase-src-testlib-doc-snippets-code-doc_src_qsignalspy.py
    :lines: 80-81

To retrieve the instance, you can use qvariant_cast:

.. literalinclude:: ../../../snippets/qtbase-src-testlib-doc-snippets-code-doc_src_qsignalspy.py
    :lines: 86-87
