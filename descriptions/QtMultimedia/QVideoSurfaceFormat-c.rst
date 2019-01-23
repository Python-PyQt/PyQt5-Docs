.. sip:class-description::
    :status: todo
    :brief: Specifies the stream format of a video presentation surface
    :digest: b7237eb442b05583b9828a1da70cd3ee

The :sip:ref:`~PyQt5.QtMultimedia.QVideoSurfaceFormat` class specifies the stream format of a video presentation surface.

A video surface presents a stream of video frames. The surface's format describes the type of the frames and determines how they should be presented.

The core properties of a video stream required to setup a video surface are the pixel format given by :sip:ref:`~PyQt5.QtMultimedia.QVideoSurfaceFormat.pixelFormat`, and the frame dimensions given by :sip:ref:`~PyQt5.QtMultimedia.QVideoSurfaceFormat.frameSize`.

If the surface is to present frames using a frame's handle a surface format will also include a handle type which is given by the :sip:ref:`~PyQt5.QtMultimedia.QVideoSurfaceFormat.handleType` function.

The region of a frame that is actually displayed on a video surface is given by the :sip:ref:`~PyQt5.QtMultimedia.QVideoSurfaceFormat.viewport`. A stream may have a viewport less than the entire region of a frame to allow for videos smaller than the nearest optimal size of a video frame. For example the width of a frame may be extended so that the start of each scan line is eight byte aligned.

Other common properties are the :sip:ref:`~PyQt5.QtMultimedia.QVideoSurfaceFormat.pixelAspectRatio`, :sip:ref:`~PyQt5.QtMultimedia.QVideoSurfaceFormat.scanLineDirection`, and :sip:ref:`~PyQt5.QtMultimedia.QVideoSurfaceFormat.frameRate`. Additionally a stream may have some additional type specific properties which are listed by the dynamicPropertyNames() function and can be accessed using the :sip:ref:`~PyQt5.QtMultimedia.QVideoSurfaceFormat.property`, and :sip:ref:`~PyQt5.QtMultimedia.QVideoSurfaceFormat.setProperty` functions.
