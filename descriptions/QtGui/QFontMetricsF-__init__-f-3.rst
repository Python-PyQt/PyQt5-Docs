.. sip:method-description::
    :status: todo
    :pysig: 72d94224d1d6e7d73e176d97075c9297
    :realsig: (const QFont&,QPaintDevice*)
    :digest: 0052db96b54ef7d8e06bc9b9ac1dc4d3

Constructs a font metrics object for *font* and *paintdevice*.

The font metrics will be compatible with the paintdevice passed. If the *paintdevice* is 0, the metrics will be screen-compatible, ie. the metrics you get if you use the font for drawing text on a :sip:ref:`~PyQt5.QtWidgets.QWidget` or :sip:ref:`~PyQt5.QtGui.QPixmap`, not on a :sip:ref:`~PyQt5.QtGui.QPicture` or QPrinter.

The font metrics object holds the information for the font that is passed in the constructor at the time it is created, and is not updated if the font's attributes are changed later.
