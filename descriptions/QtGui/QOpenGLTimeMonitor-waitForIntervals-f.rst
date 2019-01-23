.. sip:method-description::
    :status: todo
    :pysig: 547b203239a35d1de005c5b84090af5b
    :realsig: () const
    :digest: bdcbd6cdd1411b07fbf29bf972a71171

Returns a QVector containing the time intervals delimited by the calls to :sip:ref:`~PyQt5.QtGui.QOpenGLTimeMonitor.recordSample`. The resulting vector will contain one fewer element as this represents the intervening intervals rather than the actual timestamp samples.

This function will block until OpenGL indicates the results are available. It is recommended to check the availability of the result prior to calling this function with :sip:ref:`~PyQt5.QtGui.QOpenGLTimeMonitor.isResultAvailable`.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOpenGLTimeMonitor.waitForSamples`, :sip:ref:`~PyQt5.QtGui.QOpenGLTimeMonitor.isResultAvailable`.
