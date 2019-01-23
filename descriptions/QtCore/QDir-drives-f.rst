.. sip:method-description::
    :status: todo
    :pysig: 3e3577f3962659e494f946f184aaebfb
    :realsig: ()
    :digest: 2498495f0dac4dc78bdba726cd192ab7

Returns a list of the root directories on this system.

On Windows this returns a list of :sip:ref:`~PyQt5.QtCore.QFileInfo` objects containing "C:/", "D:/", etc. On other operating systems, it returns a list containing just one root directory (i.e. "/").

.. seealso:: :sip:ref:`~PyQt5.QtCore.QDir.root`, :sip:ref:`~PyQt5.QtCore.QDir.rootPath`.
