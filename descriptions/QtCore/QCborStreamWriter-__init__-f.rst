.. sip:method-description::
    :status: todo
    :pysig: 623c570a0ff0d5d7d29a7ced11b3367f
    :realsig: (QIODevice*)
    :digest: 6d7c770057e539f177ccd2d08c3255bf

Creates a :sip:ref:`~PyQt5.QtCore.QCborStreamWriter` object that will write the stream to *device*. The device must be opened before the first :sip:ref:`~PyQt5.QtCore.QCborStreamWriter.append` call is made. This constructor can be used with any class that derives from :sip:ref:`~PyQt5.QtCore.QIODevice`, such as :sip:ref:`~PyQt5.QtCore.QFile`, QProcess or :sip:ref:`~PyQt5.QtNetwork.QTcpSocket`.

:sip:ref:`~PyQt5.QtCore.QCborStreamWriter` has no buffering, so every :sip:ref:`~PyQt5.QtCore.QCborStreamWriter.append` call will result in one or more calls to the device's :sip:ref:`~PyQt5.QtCore.QIODevice.write` method.

The following example writes an empty map to a file:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_serialization_qcborstream.py
    :lines: 67-70

:sip:ref:`~PyQt5.QtCore.QCborStreamWriter` does not take ownership of *device*.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QCborStreamWriter.device`, :sip:ref:`~PyQt5.QtCore.QCborStreamWriter.setDevice`.
