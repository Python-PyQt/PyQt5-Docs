.. sip:method-description::
    :status: todo
    :pysig: 85d874f26915dc26fe3a6d18dae11ea6
    :realsig: (QEventLoop::ProcessEventsFlags)
    :digest: b3af8f54f3a20f207c5913a5f6f70677

Processes pending events that match *flags* until there are no more events to process. Returns ``true`` if pending events were handled; otherwise returns ``false``.

This function is especially useful if you have a long running operation and want to show its progress without allowing user input; i.e. by using the :sip:ref:`~PyQt5.QtCore.QEventLoop.ProcessEventsFlag.ExcludeUserInputEvents` flag.

This function is simply a wrapper for :sip:ref:`~PyQt5.QtCore.QAbstractEventDispatcher.processEvents`. See the documentation for that function for details.
