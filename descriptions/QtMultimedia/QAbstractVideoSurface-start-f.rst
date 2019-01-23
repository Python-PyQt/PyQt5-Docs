.. sip:method-description::
    :status: todo
    :pysig: 43a84277261cc80fde7d00c0db1b3467
    :realsig: (const QVideoSurfaceFormat&)
    :digest: 275860d58fd2e5036109032383fb11cc

Starts a video surface presenting *format* frames.

Returns true if the surface was started, and false if an error occurred.

**Note:** You must call the base class implementation of  at the end of your implementation.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoSurface.isActive`, :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoSurface.stop`.
