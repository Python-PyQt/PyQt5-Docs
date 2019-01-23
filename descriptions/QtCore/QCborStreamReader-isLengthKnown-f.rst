.. sip:method-description::
    :status: todo
    :pysig: c506ff134babdd6e68ab3e6350e95305
    :realsig: () const
    :digest: 2d21ac4ff9a24a2be4784c1c381e2b0d

Returns true if the length of the current array, map, byte array or string is known (explicit in the CBOR stream), false otherwise. This function should only be called if the element is one of those.

If the length is known, it may be obtained by calling .

If the length of a map or an array is not known, it is implied by the number of elements present in the stream. :sip:ref:`~PyQt5.QtCore.QCborStreamReader` has no API to calculate the length in that condition.

Strings and byte arrays may also have indeterminate length (that is, they may be transmitted in multiple chunks). Those cannot currently be created with :sip:ref:`~PyQt5.QtCore.QCborStreamWriter`, but they could be with other encoders, so :sip:ref:`~PyQt5.QtCore.QCborStreamReader` supports them.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QCborStreamWriter.startArray`, :sip:ref:`~PyQt5.QtCore.QCborStreamWriter.startMap`, :sip:ref:`~PyQt5.QtCore.QCborStreamReader.length`.
