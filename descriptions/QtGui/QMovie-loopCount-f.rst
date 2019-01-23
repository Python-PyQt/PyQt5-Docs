.. sip:method-description::
    :status: todo
    :pysig: fa7153f7ed1cb6c0fcf2ffb2fac21748
    :realsig: () const
    :digest: 86682a0df08a9e8f6248a83fa0afde90

Returns the number of times the movie will loop before it finishes. If the movie will only play once (no looping),  returns 0. If the movie loops forever,  returns -1.

Note that, if the image data comes from a sequential device (e.g. a socket), :sip:ref:`~PyQt5.QtGui.QMovie` can only loop the movie if the :sip:ref:`~PyQt5.QtGui.QMovie.cacheMode` is set to QMovie::CacheAll.
