.. sip:method-description::
    :status: todo
    :pysig: d41d8cd98f00b204e9800998ecf8427e
    :realsig: ()
    :digest: 2bbe09edbef3d9846db3ae2bc12a5a6a

This function sets the position used by :sip:ref:`~PyQt5.QtXml.QXmlInputSource.next` to the beginning of the data returned by :sip:ref:`~PyQt5.QtXml.QXmlInputSource.data`. This is useful if you want to use the input source for more than one parse.

**Note:** In the case that the underlying data source is a :sip:ref:`~PyQt5.QtCore.QIODevice`, the current position in the device is not automatically set to the start of input. Call :sip:ref:`~PyQt5.QtCore.QIODevice.seek`\ (0) on the device to do this.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QXmlInputSource.next`.
