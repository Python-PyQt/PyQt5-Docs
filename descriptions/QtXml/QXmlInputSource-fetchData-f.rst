.. sip:method-description::
    :status: todo
    :pysig: d41d8cd98f00b204e9800998ecf8427e
    :realsig: ()
    :digest: edc82b07b96a6a96203d65ae97cabcf8

This function reads more data from the device that was set during construction. If the input source already contained data, this function deletes that data first.

This object contains no data after a call to this function if the object was constructed without a device to read data from or if this function was not able to get more data from the device.

There are two occasions where a fetch is done implicitly by another function call: during construction (so that the object starts out with some initial data where available), and during a call to :sip:ref:`~PyQt5.QtXml.QXmlInputSource.next` (if the data had run out).

You don't normally need to use this function if you use :sip:ref:`~PyQt5.QtXml.QXmlInputSource.next`.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QXmlInputSource.data`, :sip:ref:`~PyQt5.QtXml.QXmlInputSource.next`, :sip:ref:`~PyQt5.QtXml.QXmlInputSource`.
