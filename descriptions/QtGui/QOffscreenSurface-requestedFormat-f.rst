.. sip:method-description::
    :status: todo
    :pysig: 28e4dad5bd4c95a17dfb30da3d108fb7
    :realsig: () const
    :digest: 56ea2efc8504a876b839a95d3802ea4b

Returns the requested surfaceformat of this offscreen surface.

If the requested format was not supported by the platform implementation, the  will differ from the actual offscreen surface format.

This is the value set with :sip:ref:`~PyQt5.QtGui.QOffscreenSurface.setFormat`.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOffscreenSurface.setFormat`, :sip:ref:`~PyQt5.QtGui.QOffscreenSurface.format`.
