.. sip:method-description::
    :status: todo
    :pysig: 8edbba181f29adf4828a943ac14ec4d0
    :realsig: (const QDomNode&)
    :digest: dfbfd5f9bcbd0659bca2b44a50c5bd78

Removes *oldChild* from the list of children. *oldChild* must be a direct child of this node.

Returns a new reference to *oldChild* on success or a :sip:ref:`~PyQt5.QtXml.QDomNode.isNull` on failure.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QDomNode.insertBefore`, :sip:ref:`~PyQt5.QtXml.QDomNode.insertAfter`, :sip:ref:`~PyQt5.QtXml.QDomNode.replaceChild`, :sip:ref:`~PyQt5.QtXml.QDomNode.appendChild`.
