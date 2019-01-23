.. sip:method-description::
    :status: todo
    :pysig: 957a27fe19390827f6fff4d53cf9c4b4
    :realsig: (int) const
    :digest: 01718a34dcc428ae0676032bdb8e7fb1

Returns the node at position *index*.

If *index* is negative or if *index* >= :sip:ref:`~PyQt5.QtXml.QDomNodeList.length` then a null node is returned (i.e. a node for which :sip:ref:`~PyQt5.QtXml.QDomNode.isNull` returns true).

.. seealso:: :sip:ref:`~PyQt5.QtXml.QDomNodeList.length`.
