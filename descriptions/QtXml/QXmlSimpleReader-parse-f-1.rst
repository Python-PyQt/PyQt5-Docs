.. sip:method-description::
    :status: todo
    :pysig: d94849c8b3ceb5eab01d41eef89b9cb6
    :realsig: (const QXmlInputSource*,bool)
    :digest: a5c0bd9fdab0937559deaf6888117251

Reads an XML document from *input* and parses it. Returns ``true`` if the parsing is completed successfully; otherwise returns ``false``, indicating that an error occurred.

If *incremental* is false, this function will return false if the XML file is not read completely. The parsing cannot be continued in this case.

If *incremental* is true, the parser does not return false if it reaches the end of the *input* before reaching the end of the XML file. Instead, it stores the state of the parser so that parsing can be continued later when more data is available. In such a case, you can use the function :sip:ref:`~PyQt5.QtXml.QXmlSimpleReader.parseContinue` to continue with parsing. This class stores a pointer to the input source *input* and the :sip:ref:`~PyQt5.QtXml.QXmlSimpleReader.parseContinue` function tries to read from that input source. Therefore, you should not delete the input source *input* until you no longer need to call :sip:ref:`~PyQt5.QtXml.QXmlSimpleReader.parseContinue`.

If this function is called with *incremental* set to true while an incremental parse is in progress, a new parsing session will be started, and the previous session will be lost.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QXmlSimpleReader.parseContinue`, :sip:ref:`~PyQt5.QtNetwork.QTcpSocket`.
