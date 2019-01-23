.. sip:method-description::
    :status: todo
    :pysig: b145cbf9885a04bb1f1d064e0fd39e53
    :realsig: (QXmlInputSource*,QXmlReader*,QString*,int*,int*)
    :digest: 4ec29b6608aa3c6d1b1fb5157d1a31db

This is an overloaded function.

This function reads the XML document from the :sip:ref:`~PyQt5.QtXml.QXmlInputSource` *source* and parses it with the :sip:ref:`~PyQt5.QtXml.QXmlReader` *reader*, returning true if the content was successfully parsed; otherwise returns ``false``.

This function doesn't change the features of the *reader*. If you want to use certain features for parsing you can use this function to set up the reader appropriately.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QXmlSimpleReader`.
