.. sip:method-description::
    :status: todo
    :pysig: 75be13ad76f68baff6b6d28c5bafddae
    :realsig: () const
    :digest: 6cffd3098e21c2771b221a0f763d1d1a

Returns the type of handle the surface uses to present the frame data.

If the handle type is ``QAbstractVideoBuffer::NoHandle``, buffers with any handle type are valid provided they can be :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoBuffer.map` with the :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoBuffer.MapMode.ReadOnly` flag. If the  is not :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoBuffer.HandleType.NoHandle` then the handle type of the buffer must be the same as that of the surface format.
