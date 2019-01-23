.. sip:method-description::
    :status: todo
    :pysig: d41d8cd98f00b204e9800998ecf8427e
    :realsig: ()
    :digest: 60abc032329a1f2f8fe532387e2c9d49

Starts a CBOR Array with indeterminate length in the CBOR stream. Each  call must be paired with one :sip:ref:`~PyQt5.QtCore.QCborStreamWriter.endArray` call and the current CBOR element extends until the end of the array.

The array created by this function has no explicit length. Instead, its length is implied by the elements contained in it. Note, however, that use of indeterminate-length arrays is not compliant with canonical CBOR encoding.

The following example appends elements from the linked list of strings passed as input:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_serialization_qcborstream.py
    :lines: 202-208

.. seealso:: startArray(quint64), :sip:ref:`~PyQt5.QtCore.QCborStreamWriter.endArray`, :sip:ref:`~PyQt5.QtCore.QCborStreamWriter.startMap`.
