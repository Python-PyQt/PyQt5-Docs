.. sip:method-description::
    :status: todo
    :pysig: 341be97d9aff90c9978347f66f945b77
    :realsig: ()
    :digest: 8a2acfe364ae84e8abd9acd34f0afb11

Returns the next character of the input source. If this function reaches the end of available data, it returns QXmlInputSource::EndOfData. If you call  after that, it tries to fetch more data by calling :sip:ref:`~PyQt5.QtXml.QXmlInputSource.fetchData`. If the :sip:ref:`~PyQt5.QtXml.QXmlInputSource.fetchData` call results in new data, this function returns the first character of that data; otherwise it returns QXmlInputSource::EndOfDocument.

Readers, such as :sip:ref:`~PyQt5.QtXml.QXmlSimpleReader`, will assume that the end of the XML document has been reached if the this function returns QXmlInputSource::EndOfDocument, and will check that the supplied input is well-formed. Therefore, when reimplementing this function, it is important to ensure that this behavior is duplicated.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QXmlInputSource.reset`, :sip:ref:`~PyQt5.QtXml.QXmlInputSource.fetchData`, :sip:ref:`~PyQt5.QtXml.QXmlSimpleReader.parse`, :sip:ref:`~PyQt5.QtXml.QXmlSimpleReader.parseContinue`.
