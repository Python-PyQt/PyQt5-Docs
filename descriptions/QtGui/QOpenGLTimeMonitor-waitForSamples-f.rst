.. sip:method-description::
    :status: todo
    :pysig: 547b203239a35d1de005c5b84090af5b
    :realsig: () const
    :digest: 2bef5b81bb4bf63a715f4c4bba70d3f4

Returns a QVector containing the GPU timestamps taken with :sip:ref:`~PyQt5.QtGui.QOpenGLTimeMonitor.recordSample`.

This function will block until OpenGL indicates the results are available. It is recommended to check the availability of the result prior to calling this function with :sip:ref:`~PyQt5.QtGui.QOpenGLTimeMonitor.isResultAvailable`.

**Note:** This function only works on systems that have OpenGL >=3.3 or the ARB_timer_query extension. See :sip:ref:`~PyQt5.QtGui.QOpenGLTimerQuery` for more details.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOpenGLTimeMonitor.waitForIntervals`, :sip:ref:`~PyQt5.QtGui.QOpenGLTimeMonitor.isResultAvailable`.
