.. sip:method-description::
    :status: todo
    :pysig: d41d8cd98f00b204e9800998ecf8427e
    :realsig: ()
    :digest: fdc1326b1bb8d3a9130aa9fc4c6e30fd

Marks the start point in the OpenGL command queue for a sequence of commands to be timed by this query object.

This is useful for simple use-cases. Usually it is better to use :sip:ref:`~PyQt5.QtGui.QOpenGLTimerQuery.recordTimestamp`.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOpenGLTimerQuery.end`, :sip:ref:`~PyQt5.QtGui.QOpenGLTimerQuery.isResultAvailable`, :sip:ref:`~PyQt5.QtGui.QOpenGLTimerQuery.waitForResult`, :sip:ref:`~PyQt5.QtGui.QOpenGLTimerQuery.recordTimestamp`.
