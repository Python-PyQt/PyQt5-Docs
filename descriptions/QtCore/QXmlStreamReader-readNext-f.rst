.. sip:method-description::
    :status: todo
    :pysig: f07c809d09f6c0144af386fdc875f2d0
    :realsig: ()
    :digest: 62dc2ae6b9b56072c4e157360c540bd8

Reads the next token and returns its type.

With one exception, once an :sip:ref:`~PyQt5.QtCore.QXmlStreamReader.error` is reported by , further reading of the XML stream is not possible. Then :sip:ref:`~PyQt5.QtCore.QXmlStreamReader.atEnd` returns ``true``, :sip:ref:`~PyQt5.QtCore.QXmlStreamReader.hasError` returns ``true``, and this function returns :sip:ref:`~PyQt5.QtCore.QXmlStreamReader.TokenType.Invalid`.

The exception is when :sip:ref:`~PyQt5.QtCore.QXmlStreamReader.error` returns :sip:ref:`~PyQt5.QtCore.QXmlStreamReader.Error.PrematureEndOfDocumentError`. This error is reported when the end of an otherwise well-formed chunk of XML is reached, but the chunk doesn't represent a complete XML document. In that case, parsing *can* be resumed by calling :sip:ref:`~PyQt5.QtCore.QXmlStreamReader.addData` to add the next chunk of XML, when the stream is being read from a :sip:ref:`~PyQt5.QtCore.QByteArray`, or by waiting for more data to arrive when the stream is being read from a :sip:ref:`~PyQt5.QtCore.QXmlStreamReader.device`.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QXmlStreamReader.tokenType`, :sip:ref:`~PyQt5.QtCore.QXmlStreamReader.tokenString`.
