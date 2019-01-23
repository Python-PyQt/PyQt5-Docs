.. sip:method-description::
    :status: todo
    :pysig: 622246bcf9e090d7c32b381c5d295d6c
    :realsig: (const QLineF*,int)
    :digest: 496e8f8ec9586f22bca7560e65197ab6

The default implementation splits the list of lines in *lines* into *lineCount* separate calls to :sip:ref:`~PyQt5.QtGui.QPaintEngine.drawPath` or :sip:ref:`~PyQt5.QtGui.QPaintEngine.drawPolygon` depending on the feature set of the paint engine.
