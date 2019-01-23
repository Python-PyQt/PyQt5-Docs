.. sip:method-description::
    :status: todo
    :pysig: 341be97d9aff90c9978347f66f945b77
    :realsig: (const QString&)
    :digest: 8602b140131ce35066d8c45bb6b3483f

Creates a new stream reader that reads from *data*.

This function should only be used if the XML header either says the encoding is "UTF-8" or lacks any encoding information (the latter is the case of :sip:ref:`~PyQt5.QtCore.QXmlStreamWriter` writing to a QString). Any other encoding is likely going to cause data corruption ("mojibake").

.. seealso:: :sip:ref:`~PyQt5.QtCore.QXmlStreamReader.addData`, :sip:ref:`~PyQt5.QtCore.QXmlStreamReader.clear`, :sip:ref:`~PyQt5.QtCore.QXmlStreamReader.setDevice`.
