.. sip:class-description::
    :status: todo
    :brief: Abstraction for video data
    :digest: f037a6542f0a1d26c714960cf65be367

The :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoBuffer` class is an abstraction for video data.

The :sip:ref:`~PyQt5.QtMultimedia.QVideoFrame` class makes use of a :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoBuffer` internally to reference a buffer of video data. Quite often video data buffers may reside in video memory rather than system memory, and this class provides an abstraction of the location.

In addition, creating a subclass of :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoBuffer` will allow you to construct video frames from preallocated or static buffers, in cases where the :sip:ref:`~PyQt5.QtMultimedia.QVideoFrame` constructors taking a :sip:ref:`~PyQt5.QtCore.QByteArray` or a :sip:ref:`~PyQt5.QtGui.QImage` do not suffice. This may be necessary when implementing a new hardware accelerated video system, for example.

The contents of a buffer can be accessed by mapping the buffer to memory using the :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoBuffer.map` function, which returns a pointer to memory containing the contents of the video buffer. The memory returned by :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoBuffer.map` is released by calling the :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoBuffer.unmap` function.

The :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoBuffer.handle` of a buffer may also be used to manipulate its contents using type specific APIs. The type of a buffer's handle is given by the :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoBuffer.handleType` function.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QVideoFrame`.
