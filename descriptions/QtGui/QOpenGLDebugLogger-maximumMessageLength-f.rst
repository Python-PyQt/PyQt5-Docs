.. sip:method-description::
    :status: todo
    :pysig: fa7153f7ed1cb6c0fcf2ffb2fac21748
    :realsig: () const
    :digest: 2958e126682b4cd70059e5fa130d07bb

Returns the maximum supported length, in bytes, for the text of the messages passed to :sip:ref:`~PyQt5.QtGui.QOpenGLDebugLogger.logMessage`. This is also the maximum length of a debug group name, as pushing or popping groups will automatically log a message with the debug group name as the message text.

If a message text is too long, it will be automatically truncated by :sip:ref:`~PyQt5.QtGui.QOpenGLDebugLogger`.

**Note:** Message texts are encoded in UTF-8 when they get passed to OpenGL, so their size in bytes does not usually match the amount of UTF-16 code units, as returned f.i. by QString::length(). (It does if the message contains 7-bit ASCII only data, which is typical for debug messages.)
