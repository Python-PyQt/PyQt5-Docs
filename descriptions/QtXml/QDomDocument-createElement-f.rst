.. sip:method-description::
    :status: todo
    :pysig: e4d54a5557bc4b9fc3bb0b5baa77ce24
    :realsig: (const QString&)
    :digest: 3f933f6b77f302aafe683e8e18f0a8fb

Creates a new element called *tagName* that can be inserted into the DOM tree, e.g. using :sip:ref:`~PyQt5.QtXml.QDomNode.appendChild`.

If *tagName* is not a valid XML name, the behavior of this function is governed by :sip:ref:`~PyQt5.QtXml.QDomImplementation.InvalidDataPolicy`.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QDomDocument.createElementNS`, :sip:ref:`~PyQt5.QtXml.QDomNode.appendChild`, :sip:ref:`~PyQt5.QtXml.QDomNode.insertBefore`, :sip:ref:`~PyQt5.QtXml.QDomNode.insertAfter`.
