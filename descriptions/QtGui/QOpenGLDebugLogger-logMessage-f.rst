.. sip:method-description::
    :status: todo
    :pysig: 5102ebcd532949cc36f59f1350408b68
    :realsig: (const QOpenGLDebugMessage&)
    :digest: dadc229fd2f7e896f1be7ca5e981758b

Inserts the message *debugMessage* into the OpenGL debug log. This provides a way for applications or libraries to insert custom messages that can ease the debugging of OpenGL applications.

**Note:** *debugMessage* must have :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Source.ApplicationSource` or :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Source.ThirdPartySource` as its source, and a valid type and severity, otherwise it will not be inserted into the log.

**Note:** The object must be initialized before logging can happen.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOpenGLDebugLogger.initialize`.
