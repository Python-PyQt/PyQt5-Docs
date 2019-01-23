.. sip:method-description::
    :status: todo
    :pysig: b902b6cf984473d268fb68cf695231e0
    :realsig: (const QCamera&)
    :digest: 30293adb5075863654d4ddfb5aedb494

Constructs a camera info object for *camera*.

You can use it to query information about the *camera* object passed as argument.

If the *camera* is invalid, for example when no camera device is available on the system, the :sip:ref:`~PyQt5.QtMultimedia.QCameraInfo` object will be invalid and :sip:ref:`~PyQt5.QtMultimedia.QCameraInfo.isNull` will return true.
