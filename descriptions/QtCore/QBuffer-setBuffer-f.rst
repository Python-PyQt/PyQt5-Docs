.. sip:method-description::
    :status: todo
    :pysig: 6359afdf86b9ec14316ea3f79e266b65
    :realsig: (QByteArray*)
    :digest: 220386c48a668bec806313f332508474

Makes :sip:ref:`~PyQt5.QtCore.QBuffer` uses the :sip:ref:`~PyQt5.QtCore.QByteArray` pointed to by *byteArray* as its internal buffer. The caller is responsible for ensuring that *byteArray* remains valid until the :sip:ref:`~PyQt5.QtCore.QBuffer` is destroyed, or until  is called to change the buffer. :sip:ref:`~PyQt5.QtCore.QBuffer` doesn't take ownership of the :sip:ref:`~PyQt5.QtCore.QByteArray`.

Does nothing if isOpen() is true.

If you open the buffer in write-only mode or read-write mode and write something into the :sip:ref:`~PyQt5.QtCore.QBuffer`, *byteArray* will be modified.

Example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-buffer-buffer.py
    :lines: 115-122

If *byteArray* is 0, the buffer creates its own internal :sip:ref:`~PyQt5.QtCore.QByteArray` to work on. This byte array is initially empty.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QBuffer.buffer`, :sip:ref:`~PyQt5.QtCore.QBuffer.setData`, :sip:ref:`~PyQt5.QtCore.QBuffer.open`.
