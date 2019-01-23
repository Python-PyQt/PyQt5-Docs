.. sip:method-description::
    :status: todo
    :pysig: ac88d0f3e1842f011af2d169e46f38df
    :realsig: (const QDomNode&,const QDomNode&)
    :digest: 43377a3a1ad732d500e77acc47fbc741

Inserts the node *newChild* before the child node *refChild*. *refChild* must be a direct child of this node. If *refChild* is :sip:ref:`~PyQt5.QtXml.QDomNode.isNull` then *newChild* is inserted as the node's first child.

If *newChild* is the child of another node, it is reparented to this node. If *newChild* is a child of this node, then its position in the list of children is changed.

If *newChild* is a :sip:ref:`~PyQt5.QtXml.QDomDocumentFragment`, then the children of the fragment are removed from the fragment and inserted before *refChild*.

Returns a new reference to *newChild* on success or a :sip:ref:`~PyQt5.QtXml.QDomNode.isNull` on failure.

The DOM specification disallow inserting attribute nodes, but due to historical reasons QDom accept them nevertheless.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QDomNode.insertAfter`, :sip:ref:`~PyQt5.QtXml.QDomNode.replaceChild`, :sip:ref:`~PyQt5.QtXml.QDomNode.removeChild`, :sip:ref:`~PyQt5.QtXml.QDomNode.appendChild`.
