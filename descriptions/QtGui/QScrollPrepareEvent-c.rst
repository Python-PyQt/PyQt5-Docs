.. sip:class-description::
    :status: todo
    :brief: Sent in preparation of scrolling
    :digest: a3170bc991dcc713ed7bba45a1626099

The :sip:ref:`~PyQt5.QtGui.QScrollPrepareEvent` class is sent in preparation of scrolling.

The scroll prepare event is sent before scrolling (usually by QScroller) is started. The object receiving this event should set :sip:ref:`~PyQt5.QtGui.QScrollPrepareEvent.viewportSize`, maxContentPos and :sip:ref:`~PyQt5.QtGui.QScrollPrepareEvent.contentPos`. It also should accept this event to indicate that scrolling should be started.

It is not guaranteed that a :sip:ref:`~PyQt5.QtGui.QScrollEvent` will be sent after an acceepted :sip:ref:`~PyQt5.QtGui.QScrollPrepareEvent`, e.g. in a case where the maximum content position is (0,0).

.. seealso:: :sip:ref:`~PyQt5.QtGui.QScrollEvent`.
