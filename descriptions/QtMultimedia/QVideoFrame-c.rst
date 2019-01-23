.. sip:class-description::
    :status: todo
    :brief: Represents a frame of video data
    :digest: a00689a5a00efc24b34fbb23b4fbdfce

The :sip:ref:`~PyQt5.QtMultimedia.QVideoFrame` class represents a frame of video data.

A :sip:ref:`~PyQt5.QtMultimedia.QVideoFrame` encapsulates the pixel data of a video frame, and information about the frame.

Video frames can come from several places - decoded :sip:ref:`~PyQt5.QtMultimedia.QMediaPlayer`, a :sip:ref:`~PyQt5.QtMultimedia.QCamera`, or generated programmatically. The way pixels are described in these frames can vary greatly, and some pixel formats offer greater compression opportunities at the expense of ease of use.

The pixel contents of a video frame can be mapped to memory using the :sip:ref:`~PyQt5.QtMultimedia.QVideoFrame.map` function. While mapped, the video data can accessed using the :sip:ref:`~PyQt5.QtMultimedia.QVideoFrame.bits` function, which returns a pointer to a buffer. The total size of this buffer is given by the :sip:ref:`~PyQt5.QtMultimedia.QVideoFrame.mappedBytes` function, and the size of each line is given by :sip:ref:`~PyQt5.QtMultimedia.QVideoFrame.bytesPerLine`. The return value of the :sip:ref:`~PyQt5.QtMultimedia.QVideoFrame.handle` function may also be used to access frame data using the internal buffer's native APIs (for example - an OpenGL texture handle).

A video frame can also have timestamp information associated with it. These timestamps can be used by an implementation of :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoSurface` to determine when to start and stop displaying the frame, but not all surfaces might respect this setting.

The video pixel data in a :sip:ref:`~PyQt5.QtMultimedia.QVideoFrame` is encapsulated in a :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoBuffer`. A :sip:ref:`~PyQt5.QtMultimedia.QVideoFrame` may be constructed from any buffer type by subclassing the :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoBuffer` class.

**Note:** Since video frames can be expensive to copy, :sip:ref:`~PyQt5.QtMultimedia.QVideoFrame` is explicitly shared, so any change made to a video frame will also apply to any copies.
