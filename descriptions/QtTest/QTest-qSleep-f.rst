.. sip:method-description::
    :status: todo
    :pysig: 5cd04cdbb9ebf068a865ec63c9099761
    :realsig: (int)
    :digest: 44ecb972f0887f8a534f2cdada06a7b8

Sleeps for *ms* milliseconds, blocking execution of the test.  will not do any event processing and leave your test unresponsive. Network communication might time out while sleeping. Use :sip:ref:`~PyQt5.QtTest.QTest.qWait` to do non-blocking sleeping.

*ms* must be greater than 0.

**Note:** The  function calls either ``nanosleep()`` on unix or ``Sleep()`` on windows, so the accuracy of time spent in  depends on the operating system.

Example:

.. literalinclude:: ../../../snippets/qtbase-src-testlib-doc-snippets-code-src_qtestlib_qtestcase.py
    :lines: 240-240

.. seealso:: :sip:ref:`~PyQt5.QtTest.QTest.qWait`.
