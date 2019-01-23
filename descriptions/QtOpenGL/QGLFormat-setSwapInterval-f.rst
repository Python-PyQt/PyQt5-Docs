.. sip:method-description::
    :status: todo
    :pysig: fa7153f7ed1cb6c0fcf2ffb2fac21748
    :realsig: (int)
    :digest: d6a6a78ab55317c37a4a7db4ff4402b9

Set the preferred swap interval. This can be used to sync the GL drawing into a system window to the vertical refresh of the screen. Setting an *interval* value of 0 will turn the vertical refresh syncing off, any value higher than 0 will turn the vertical syncing on.

Under Windows and under X11, where the ``WGL_EXT_swap_control`` and ``GLX_SGI_video_sync`` extensions are used, the *interval* parameter can be used to set the minimum number of video frames that are displayed before a buffer swap will occur. In effect, setting the *interval* to 10, means there will be 10 vertical retraces between every buffer swap.

Under Windows the ``WGL_EXT_swap_control`` extension has to be present, and under X11 the ``GLX_SGI_video_sync`` extension has to be present.

.. seealso:: :sip:ref:`~PyQt5.QtOpenGL.QGLFormat.swapInterval`.
