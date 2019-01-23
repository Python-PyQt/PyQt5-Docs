.. sip:class-description::
    :status: todo
    :brief: Used to report errors with the QXmlErrorHandler interface
    :digest: bfb3018cc052d86b1ea438885dbfc62b

The :sip:ref:`~PyQt5.QtXml.QXmlParseException` class is used to report errors with the :sip:ref:`~PyQt5.QtXml.QXmlErrorHandler` interface.

The XML subsystem constructs an instance of this class when it detects an error. You can retrieve the place where the error occurred using :sip:ref:`~PyQt5.QtXml.QXmlParseException.systemId`, :sip:ref:`~PyQt5.QtXml.QXmlParseException.publicId`, :sip:ref:`~PyQt5.QtXml.QXmlParseException.lineNumber` and :sip:ref:`~PyQt5.QtXml.QXmlParseException.columnNumber`, along with the error :sip:ref:`~PyQt5.QtXml.QXmlParseException.message`. The possible error messages are:

* "no error occurred"

* "error triggered by consumer"

* "unexpected end of file"

* "more than one document type definition"

* "error occurred while parsing element"

* "tag mismatch"

* "error occurred while parsing content"

* "unexpected character"

* "invalid name for processing instruction"

* "version expected while reading the XML declaration"

* "wrong value for standalone declaration"

* "encoding declaration or standalone declaration expected while reading the XML declaration"

* "standalone declaration expected while reading the XML declaration"

* "error occurred while parsing document type definition"

* "letter is expected"

* "error occurred while parsing comment"

* "error occurred while parsing reference"

* "internal general entity reference not allowed in DTD"

* "external parsed general entity reference not allowed in attribute value"

* "external parsed general entity reference not allowed in DTD"

* "unparsed entity reference n wrong context"

* "recursive entities"

* "error in the text declaration of an external entity"

Note that, if you want to display these error messages to your application's users, they will be displayed in English unless they are explicitly translated.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QXmlErrorHandler`, :sip:ref:`~PyQt5.QtXml.QXmlReader`.
