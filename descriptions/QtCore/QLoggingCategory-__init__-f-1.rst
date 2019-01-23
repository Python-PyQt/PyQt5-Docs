.. sip:method-description::
    :status: todo
    :pysig: a31459e305d4b8986b1781c8d0352765
    :realsig: (const char*,QtMsgType)
    :digest: 514deca130f6789923bac236eea0eab7

Constructs a :sip:ref:`~PyQt5.QtCore.QLoggingCategory` object with the provided *category* name, and enables all messages with types more severe or equal than *enableForLevel*.

If *category* is ``0``, the category name is changed to ``"default"``.

Note that *category* must be kept valid during the lifetime of this object.
