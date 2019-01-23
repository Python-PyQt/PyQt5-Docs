.. sip:method-description::
    :status: todo
    :pysig: 62f63e09cf8b2bc15c56d1b562ef9090
    :realsig: (const QFont&)
    :digest: a2f484464fce783718a3c56c1c0b0e78

Constructs a font info object for *font*.

The font must be screen-compatible, i.e. a font you use when drawing text in :sip:ref:`~PyQt5.QtWidgets.QWidget` or :sip:ref:`~PyQt5.QtGui.QPixmap`, not :sip:ref:`~PyQt5.QtGui.QPicture` or QPrinter.

The font info object holds the information for the font that is passed in the constructor at the time it is created, and is not updated if the font's attributes are changed later.

Use :sip:ref:`~PyQt5.QtGui.QPainter.fontInfo` to get the font info when painting. This will give correct results also when painting on paint device that is not screen-compatible.
