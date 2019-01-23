.. sip:class-description::
    :status: todo
    :brief: Base class for video presentation surfaces
    :digest: ca47c34cb90a15eb8dc03f987615816e

The :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoSurface` class is a base class for video presentation surfaces.

The :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoSurface` class defines the standard interface that video producers use to inter-operate with video presentation surfaces. You can subclass this interface to receive video frames from sources like :sip:ref:`~PyQt5.QtMultimedia.QMediaPlayer` or :sip:ref:`~PyQt5.QtMultimedia.QCamera` to perform your own processing.

A video surface presents a continuous stream of identically formatted :sip:ref:`~PyQt5.QtMultimedia.QVideoFrame` instances, where the format of each frame is compatible with a stream format supplied when starting a presentation. Each frame may have timestamp information that can be used by the surface to decide when to display that frame.

A list of pixel formats a surface can present is given by the :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoSurface.supportedPixelFormats` function, and the :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoSurface.isFormatSupported` function will test if a video surface format is supported. If a format is not supported the :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoSurface.nearestFormat` function may be able to suggest a similar format. For example, if a surface supports fixed set of resolutions it may suggest the smallest supported resolution that contains the proposed resolution.

The :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoSurface.start` function takes a supported format and enables a video surface. Once started a surface will begin displaying the frames it receives in the :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoSurface.present` function. Surfaces may hold a reference to the buffer of a presented video frame until a new frame is presented or streaming is stopped. In addition, a video surface may hold a reference to a video frame until the :sip:ref:`~PyQt5.QtMultimedia.QVideoFrame.endTime` has passed. The :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoSurface.stop` function will disable a surface and release any video buffers it holds references to.

.. _qabstractvideosurface-implementing-a-subclass-of-qabstractvideosurface:

Implementing a subclass of QAbstractVideoSurface
................................................

When implementing a subclass of this interface, there are only a handful of functions to implement, broken down into two classes:

* Format related

* Presentation related

For format related functionality, you just have to describe the pixel formats that you support (and the :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoSurface.nearestFormat` function). For presentation related functionality, you have to implement the :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoSurface.present` function, and the :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoSurface.start` and :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoSurface.stop` functions.

**Note:** You must call the base class implementation of :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoSurface.start` and :sip:ref:`~PyQt5.QtMultimedia.QAbstractVideoSurface.stop` in your implementation.
