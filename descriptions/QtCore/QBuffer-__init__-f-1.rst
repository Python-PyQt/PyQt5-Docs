.. sip:method-description::
    :status: todo
    :pysig: 4b49e2cd123334ff01cdd9d288742a9c
    :realsig: (QByteArray*,QObject*)
    :digest: 9b90659a3a1a9a1be349e778463228c5

Constructs a :sip:ref:`~PyQt5.QtCore.QBuffer` that uses the :sip:ref:`~PyQt5.QtCore.QByteArray` pointed to by *byteArray* as its internal buffer, and with the given *parent*. The caller is responsible for ensuring that *byteArray* remains valid until the :sip:ref:`~PyQt5.QtCore.QBuffer` is destroyed, or until :sip:ref:`~PyQt5.QtCore.QBuffer.setBuffer` is called to change the buffer. :sip:ref:`~PyQt5.QtCore.QBuffer` doesn't take ownership of the :sip:ref:`~PyQt5.QtCore.QByteArray`.

If you open the buffer in write-only mode or read-write mode and write something into the :sip:ref:`~PyQt5.QtCore.QBuffer`, *byteArray* will be modified.

Example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-buffer-buffer.py
    :lines: 102-108

.. seealso:: :sip:ref:`~PyQt5.QtCore.QBuffer.open`, :sip:ref:`~PyQt5.QtCore.QBuffer.setBuffer`, :sip:ref:`~PyQt5.QtCore.QBuffer.setData`.
