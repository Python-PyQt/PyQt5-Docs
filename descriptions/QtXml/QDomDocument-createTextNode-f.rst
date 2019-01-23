.. sip:method-description::
    :status: todo
    :pysig: 9e86dcc779cb12e669576e91f8b8f2aa
    :realsig: (const QString&)
    :digest: 67298b96bb3492ac78071b99390d96fc

Creates a text node for the string *value* that can be inserted into the document tree, e.g. using :sip:ref:`~PyQt5.QtXml.QDomNode.appendChild`.

If *value* contains characters which cannot be stored as character data of an XML document (even in the form of character references), the behavior of this function is governed by :sip:ref:`~PyQt5.QtXml.QDomImplementation.InvalidDataPolicy`.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QDomNode.appendChild`, :sip:ref:`~PyQt5.QtXml.QDomNode.insertBefore`, :sip:ref:`~PyQt5.QtXml.QDomNode.insertAfter`.
