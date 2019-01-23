.. sip:method-description::
    :status: todo
    :pysig: fa7153f7ed1cb6c0fcf2ffb2fac21748
    :realsig: () const
    :digest: 1d71762491f52f8f8c19568b4162d23a

Returns the length of the string or byte array, or the number of items in an array or the number, of item pairs in a map, if known. This function must not be called if the length is unknown (that is, if  returned false). It is an error to do that and it will cause :sip:ref:`~PyQt5.QtCore.QCborStreamReader` to stop parsing the input stream.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QCborStreamWriter.startArray`, :sip:ref:`~PyQt5.QtCore.QCborStreamWriter.startMap`, :sip:ref:`~PyQt5.QtCore.QCborStreamReader.isLengthKnown`.
