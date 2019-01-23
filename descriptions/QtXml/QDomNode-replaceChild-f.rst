.. sip:method-description::
    :status: todo
    :pysig: ac88d0f3e1842f011af2d169e46f38df
    :realsig: (const QDomNode&,const QDomNode&)
    :digest: e716efe7a18345f985c6667ba6fa7ab6

Replaces *oldChild* with *newChild*. *oldChild* must be a direct child of this node.

If *newChild* is the child of another node, it is reparented to this node. If *newChild* is a child of this node, then its position in the list of children is changed.

If *newChild* is a :sip:ref:`~PyQt5.QtXml.QDomDocumentFragment`, then *oldChild* is replaced by all of the children of the fragment.

Returns a new reference to *oldChild* on success or a :sip:ref:`~PyQt5.QtXml.QDomNode.isNull` on failure.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QDomNode.insertBefore`, :sip:ref:`~PyQt5.QtXml.QDomNode.insertAfter`, :sip:ref:`~PyQt5.QtXml.QDomNode.removeChild`, :sip:ref:`~PyQt5.QtXml.QDomNode.appendChild`.
