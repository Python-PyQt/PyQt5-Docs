.. sip:class-description::
    :status: todo
    :brief: Used to simulate a sequence of touch events
    :digest: f9356c794efe32479cb39c0f9091893b

The :sip:ref:`~PyQt5.QtTest.QTest.QTouchEventSequence` class is used to simulate a sequence of touch events.

To simulate a sequence of touch events on a specific device for a window or widget, call :sip:ref:`~PyQt5.QtTest.QTest.touchEvent` to create a :sip:ref:`~PyQt5.QtTest.QTest.QTouchEventSequence` instance. Add touch events to the sequence by calling :sip:ref:`~PyQt5.QtTest.QTest.QTouchEventSequence.press`, :sip:ref:`~PyQt5.QtTest.QTest.QTouchEventSequence.move`, :sip:ref:`~PyQt5.QtTest.QTest.QTouchEventSequence.release` and :sip:ref:`~PyQt5.QtTest.QTest.QTouchEventSequence.stationary`, and let the instance run out of scope to commit the sequence to the event system.

Example:

.. literalinclude:: ../../../snippets/qtbase-src-testlib-doc-snippets-code-src_qtestlib_qtestcase.py
    :lines: 245-258
