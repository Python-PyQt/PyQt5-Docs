.. sip:method-description::
    :status: todo
    :pysig: 6a42cf406ee1cc8f38318fa072cf67a2
    :realsig: (const QTransform&,const QFont&)
    :digest: 2e46921d1ebe6ba392e17c0e3f6f5b52

Prepares the :sip:ref:`~PyQt5.QtGui.QStaticText` object for being painted with the given *matrix* and the given *font* to avoid overhead when the actual drawStaticText() call is made.

When drawStaticText() is called, the layout of the :sip:ref:`~PyQt5.QtGui.QStaticText` will be recalculated if any part of the :sip:ref:`~PyQt5.QtGui.QStaticText` object has changed since the last time it was drawn. It will also be recalculated if the painter's font is not the same as when the :sip:ref:`~PyQt5.QtGui.QStaticText` was last drawn, or, on any other paint engine than the OpenGL2 engine, if the painter's matrix has been altered since the static text was last drawn.

To avoid the overhead of creating the layout the first time you draw the :sip:ref:`~PyQt5.QtGui.QStaticText` after making changes, you can use the  function and pass in the *matrix* and *font* you expect to use when drawing the text.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPainter.setFont`, QPainter::setMatrix().
