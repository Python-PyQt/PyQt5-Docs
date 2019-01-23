.. sip:method-description::
    :status: todo
    :pysig: b42207a21f9e7a7a9537ca33667f19cf
    :realsig: (QObject*)
    :digest: b54abc72ce7ed5279a775a5bc461002b

Bind *object* to this :sip:ref:`~PyQt5.QtMultimedia.QMediaObject` instance.

This method establishes a relationship between this media object and a helper object. The nature of the relationship depends on both parties. This methods returns true if the helper was successfully bound, false otherwise.

Most subclasses of :sip:ref:`~PyQt5.QtMultimedia.QMediaObject` provide more convenient functions that wrap this functionality, so this function rarely needs to be called directly.

The object passed must implement the QMediaBindableInterface interface.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QMediaBindableInterface`.
