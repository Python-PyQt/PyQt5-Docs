.. sip:method-description::
    :status: todo
    :pysig: 38f7d81f0f5c9ee70d4e106d6d27212a
    :realsig: (const QSize&,const uchar*,QImage::Format)
    :digest: 240adc30531de1017c94805a7162cb7f

Constructs a bitmap with the given *size*, and sets the contents to the *bits* supplied.

The bitmap data has to be byte aligned and provided in in the bit order specified by *monoFormat*. The mono format must be either :sip:ref:`~PyQt5.QtGui.QImage.Format.Format_Mono` or :sip:ref:`~PyQt5.QtGui.QImage.Format.Format_MonoLSB`. Use :sip:ref:`~PyQt5.QtGui.QImage.Format.Format_Mono` to specify data on the XBM format.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QBitmap.fromImage`.
