.. sip:class-description::
    :status: todo
    :brief: Convenience class for playing movies with QImageReader
    :digest: 5dec9308b83872dc997c651cc72537b0

The :sip:ref:`~PyQt5.QtGui.QMovie` class is a convenience class for playing movies with :sip:ref:`~PyQt5.QtGui.QImageReader`.

This class is used to show simple animations without sound. If you want to display video and media content, use the `Qt Multimedia <https://doc.qt.io/qt-5/qtmultimedia-index.html>`_ multimedia framework instead.

First, create a :sip:ref:`~PyQt5.QtGui.QMovie` object by passing either the name of a file or a pointer to a :sip:ref:`~PyQt5.QtCore.QIODevice` containing an animated image format to :sip:ref:`~PyQt5.QtGui.QMovie`'s constructor. You can call :sip:ref:`~PyQt5.QtGui.QMovie.isValid` to check if the image data is valid, before starting the movie. To start the movie, call :sip:ref:`~PyQt5.QtGui.QMovie.start`. :sip:ref:`~PyQt5.QtGui.QMovie` will enter :sip:ref:`~PyQt5.QtGui.QMovie.MovieState.Running` state, and emit :sip:ref:`~PyQt5.QtGui.QMovie.started` and :sip:ref:`~PyQt5.QtGui.QMovie.stateChanged`. To get the current state of the movie, call :sip:ref:`~PyQt5.QtGui.QMovie.state`.

To display the movie in your application, you can pass your :sip:ref:`~PyQt5.QtGui.QMovie` object to QLabel::setMovie(). Example:

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-code-src_gui_image_qmovie.py
    :lines: 54-58

Whenever a new frame is available in the movie, :sip:ref:`~PyQt5.QtGui.QMovie` will emit :sip:ref:`~PyQt5.QtGui.QMovie.updated`. If the size of the frame changes, :sip:ref:`~PyQt5.QtGui.QMovie.resized` is emitted. You can call :sip:ref:`~PyQt5.QtGui.QMovie.currentImage` or :sip:ref:`~PyQt5.QtGui.QMovie.currentPixmap` to get a copy of the current frame. When the movie is done, :sip:ref:`~PyQt5.QtGui.QMovie` emits :sip:ref:`~PyQt5.QtGui.QMovie.finished`. If any error occurs during playback (i.e, the image file is corrupt), :sip:ref:`~PyQt5.QtGui.QMovie` will emit :sip:ref:`~PyQt5.QtGui.QMovie.error`.

You can control the speed of the movie playback by calling :sip:ref:`~PyQt5.QtGui.QMovie.setSpeed`, which takes the percentage of the original speed as an argument. Pause the movie by calling :sip:ref:`~PyQt5.QtGui.QMovie.setPaused`\ (true). :sip:ref:`~PyQt5.QtGui.QMovie` will then enter :sip:ref:`~PyQt5.QtGui.QMovie.MovieState.Paused` state and emit :sip:ref:`~PyQt5.QtGui.QMovie.stateChanged`. If you call :sip:ref:`~PyQt5.QtGui.QMovie.setPaused`\ (false), :sip:ref:`~PyQt5.QtGui.QMovie` will reenter :sip:ref:`~PyQt5.QtGui.QMovie.MovieState.Running` state and start the movie again. To stop the movie, call :sip:ref:`~PyQt5.QtGui.QMovie.stop`.

Certain animation formats allow you to set the background color. You can call :sip:ref:`~PyQt5.QtGui.QMovie.setBackgroundColor` to set the color, or :sip:ref:`~PyQt5.QtGui.QMovie.backgroundColor` to retrieve the current background color.

:sip:ref:`~PyQt5.QtGui.QMovie.currentFrameNumber` returns the sequence number of the current frame. The first frame in the animation has the sequence number 0. :sip:ref:`~PyQt5.QtGui.QMovie.frameCount` returns the total number of frames in the animation, if the image format supports this. You can call :sip:ref:`~PyQt5.QtGui.QMovie.loopCount` to get the number of times the movie should loop before finishing. :sip:ref:`~PyQt5.QtGui.QMovie.nextFrameDelay` returns the number of milliseconds the current frame should be displayed.

:sip:ref:`~PyQt5.QtGui.QMovie` can be instructed to cache frames of an animation by calling :sip:ref:`~PyQt5.QtGui.QMovie.setCacheMode`.

Call :sip:ref:`~PyQt5.QtGui.QMovie.supportedFormats` for a list of formats that :sip:ref:`~PyQt5.QtGui.QMovie` supports.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QImageReader`, `Movie Example <https://doc.qt.io/qt-5/qtwidgets-widgets-movie-example.html>`_, :sip:ref:`~PyQt5.QtWidgets.QLabel`.
