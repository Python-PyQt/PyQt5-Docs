.. sip:class-description::
    :status: todo
    :brief: Contains event parameters for expose events
    :digest: 4bb755ab3bbe61efc1b0e7c8da1e92b8

The :sip:ref:`~PyQt5.QtGui.QExposeEvent` class contains event parameters for expose events.

Expose events are sent to windows when an area of the window is invalidated, for example when window exposure in the windowing system changes.

A Window with a client area that is completely covered by another window, or is otherwise not visible may be considered obscured by Qt and may in such cases not receive expose events.

The event handler :sip:ref:`~PyQt5.QtGui.QWindow.exposeEvent` receives expose events.
