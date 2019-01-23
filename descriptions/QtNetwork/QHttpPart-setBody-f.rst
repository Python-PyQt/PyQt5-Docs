.. sip:method-description::
    :status: todo
    :pysig: f4b16e65d42ad609ac1af344eee47372
    :realsig: (const QByteArray&)
    :digest: 69d7b6e225a9f6a15e2d6b37754b8d85

Sets the body of this MIME part to *body*. The body set with this method will be used unless the device is set via :sip:ref:`~PyQt5.QtNetwork.QHttpPart.setBodyDevice`. For a large amount of data (e.g. an image), use :sip:ref:`~PyQt5.QtNetwork.QHttpPart.setBodyDevice`, which will not copy the data internally.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QHttpPart.setBodyDevice`.
