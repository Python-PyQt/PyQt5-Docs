.. sip:method-description::
    :status: todo
    :pysig: f9f5a0ed3f19920d01f4ae374b59feaa
    :realsig: (const QString&)
    :digest: 9f22b472142135a2f30c7f466e6ef3f5

Creates a new entity reference called *name* that can be inserted into the document, e.g. using :sip:ref:`~PyQt5.QtXml.QDomNode.appendChild`.

If *name* is not a valid XML name, the behavior of this function is governed by :sip:ref:`~PyQt5.QtXml.QDomImplementation.InvalidDataPolicy`.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QDomNode.appendChild`, :sip:ref:`~PyQt5.QtXml.QDomNode.insertBefore`, :sip:ref:`~PyQt5.QtXml.QDomNode.insertAfter`.
