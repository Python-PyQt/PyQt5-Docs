.. sip:method-description::
    :status: todo
    :pysig: c506ff134babdd6e68ab3e6350e95305
    :realsig: ()
    :digest: 174778f969a98f393f4d9a7cc8cb8872

Continues incremental parsing, taking input from the :sip:ref:`~PyQt5.QtXml.QXmlInputSource` that was specified with the most recent call to :sip:ref:`~PyQt5.QtXml.QXmlSimpleReader.parse`. To use this function, you *must* have called :sip:ref:`~PyQt5.QtXml.QXmlSimpleReader.parse` with the incremental argument set to true.

Returns ``false`` if a parsing error occurs; otherwise returns ``true``, even if the end of the XML file has not been reached. You can continue parsing at a later stage by calling this function again when there is more data available to parse.

Calling this function when there is no data available in the input source indicates to the reader that the end of the XML file has been reached. If the input supplied up to this point was not well-formed then a parsing error occurs, and false is returned. If the input supplied was well-formed, true is returned. It is important to end the input in this way because it allows you to reuse the reader to parse other XML files.

Calling this function after the end of file has been reached, but without available data will cause false to be returned whether the previous input was well-formed or not.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QXmlSimpleReader.parse`, :sip:ref:`~PyQt5.QtXml.QXmlInputSource.data`, :sip:ref:`~PyQt5.QtXml.QXmlInputSource.next`.
