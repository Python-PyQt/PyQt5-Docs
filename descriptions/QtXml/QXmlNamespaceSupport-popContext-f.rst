.. sip:method-description::
    :status: todo
    :pysig: d41d8cd98f00b204e9800998ecf8427e
    :realsig: ()
    :digest: 17bbbcf014fcc454db01aed69cedf9fb

Reverts to the previous namespace context.

Normally, you should pop the context at the end of each XML element. After popping the context, all namespace prefix mappings that were previously in force are restored.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QXmlNamespaceSupport.pushContext`.
