.. sip:method-description::
    :status: todo
    :pysig: d41d8cd98f00b204e9800998ecf8427e
    :realsig: ()
    :digest: 295bd36f46088b799ed4e3595adc5a43

Starts a new namespace context.

Normally, you should push a new context at the beginning of each XML element: the new context automatically inherits the declarations of its parent context, and it also keeps track of which declarations were made within this context.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QXmlNamespaceSupport.popContext`.
