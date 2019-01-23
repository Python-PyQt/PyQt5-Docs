.. sip:enum-description::
    :status: todo
    :digest: 97365defebf8c66cab4565003f8b112a

This enum type defines the valid event types in Qt. The event types and the specialized classes for each type are as follows:

User events should have values between ``User`` and ``MaxUser``:

For convenience, you can use the :sip:ref:`~PyQt5.QtCore.QEvent.registerEventType` function to register and reserve a custom event type for your application. Doing so will allow you to avoid accidentally re-using a custom event type already in use elsewhere in your application.
