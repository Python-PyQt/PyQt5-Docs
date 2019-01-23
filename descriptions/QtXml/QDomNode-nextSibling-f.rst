.. sip:method-description::
    :status: todo
    :pysig: 6855929f20140ef8879a8596f1aac471
    :realsig: () const
    :digest: 50d7f0c323a0fb3c4a3f2eea1869334d

Returns the next sibling in the document tree. Changing the returned node will also change the node in the document tree.

If you have XML like this:

.. literalinclude:: ../../../snippets/qtbase-src-xml-doc-snippets-code-src_xml_dom_qdom.py
    :lines: 116-118

and this :sip:ref:`~PyQt5.QtXml.QDomNode` represents the <p> tag,  will return the node representing the <h2> tag.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QDomNode.previousSibling`.
