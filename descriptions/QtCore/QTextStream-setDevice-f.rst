.. sip:method-description::
    :status: todo
    :pysig: 623c570a0ff0d5d7d29a7ced11b3367f
    :realsig: (QIODevice*)
    :digest: 8c37850f8d4a7157a48b5fb9d5f32657

Sets the current device to *device*. If a device has already been assigned, :sip:ref:`~PyQt5.QtCore.QTextStream` will call :sip:ref:`~PyQt5.QtCore.flush` before the old device is replaced.

**Note:** This function resets locale to the default locale ('C') and codec to the default codec, :sip:ref:`~PyQt5.QtCore.QTextCodec.codecForLocale`.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QTextStream.device`, setString().
