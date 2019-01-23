.. sip:class-description::
    :status: todo
    :brief: Formatting information for images in a QTextDocument
    :digest: 65239135207a47498fa33788cff8d966

The :sip:ref:`~PyQt5.QtGui.QTextImageFormat` class provides formatting information for images in a :sip:ref:`~PyQt5.QtGui.QTextDocument`.

Inline images are represented by a Unicode value U+FFFC (OBJECT REPLACEMENT CHARACTER) which has an associated :sip:ref:`~PyQt5.QtGui.QTextImageFormat`. The image format specifies a name with :sip:ref:`~PyQt5.QtGui.QTextImageFormat.setName` that is used to locate the image. The size of the rectangle that the image will occupy is specified in pixels using :sip:ref:`~PyQt5.QtGui.QTextImageFormat.setWidth` and :sip:ref:`~PyQt5.QtGui.QTextImageFormat.setHeight`. The desired image quality may be set with .

Images can be supplied in any format for which Qt has an image reader, so SVG drawings can be included alongside PNG, TIFF and other bitmap formats.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QImage`, :sip:ref:`~PyQt5.QtGui.QImageReader`.
