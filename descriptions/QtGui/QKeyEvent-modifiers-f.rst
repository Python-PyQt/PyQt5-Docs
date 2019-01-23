.. sip:method-description::
    :status: todo
    :pysig: dd99639cb6e3e6896d96da602ab59899
    :realsig: () const
    :digest: fb6a3ed5b0303f0f7c861125293895d8

Returns the keyboard modifier flags that existed immediately after the event occurred.

**Warning:** This function cannot always be trusted. The user can confuse it by pressing both Shift keys simultaneously and releasing one of them, for example.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QGuiApplication.keyboardModifiers`.
