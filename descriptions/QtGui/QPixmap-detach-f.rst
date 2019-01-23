.. sip:method-description::
    :status: todo
    :pysig: d41d8cd98f00b204e9800998ecf8427e
    :realsig: ()
    :digest: 7a6ba7c5a7386e607bc2e4d3ca0a74c9

Detaches the pixmap from shared pixmap data.

A pixmap is automatically detached by Qt whenever its contents are about to change. This is done in almost all :sip:ref:`~PyQt5.QtGui.QPixmap` member functions that modify the pixmap (\ :sip:ref:`~PyQt5.QtGui.QPixmap.fill`, :sip:ref:`~PyQt5.QtGui.QPixmap.fromImage`, :sip:ref:`~PyQt5.QtGui.QPixmap.load`, etc.), and in :sip:ref:`~PyQt5.QtGui.QPainter.begin` on a pixmap.

There are two exceptions in which  must be called explicitly, that is when calling the handle() or the x11PictureHandle() function (only available on X11). Otherwise, any modifications done using system calls, will be performed on the shared data.

The  function returns immediately if there is just a single reference or if the pixmap has not been initialized yet.
