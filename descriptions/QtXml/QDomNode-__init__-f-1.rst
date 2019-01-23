.. sip:method-description::
    :status: todo
    :pysig: 6855929f20140ef8879a8596f1aac471
    :realsig: (const QDomNode&)
    :digest: 61022c17cc1de5fbfaecabb4ebfa4c6f

Constructs a copy of *n*.

The data of the copy is shared (shallow copy): modifying one node will also change the other. If you want to make a deep copy, use :sip:ref:`~PyQt5.QtXml.QDomNode.cloneNode`.
