.. sip:method-description::
    :status: todo
    :pysig: 623c570a0ff0d5d7d29a7ced11b3367f
    :realsig: (QIODevice*)
    :digest: 3ec91bcd24a2f6e44be27139a043adda

Constructs an input source and gets the data from device *dev*. If *dev* is not open, it is opened in read-only mode. If *dev* is 0 or it is not possible to read from the device, the input source will contain no data.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QXmlInputSource.setData`, :sip:ref:`~PyQt5.QtXml.QXmlInputSource.fetchData`, :sip:ref:`~PyQt5.QtCore.QIODevice`.
