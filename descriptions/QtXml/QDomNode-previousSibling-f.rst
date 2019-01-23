.. sip:method-description::
    :status: todo
    :pysig: 6855929f20140ef8879a8596f1aac471
    :realsig: () const
    :digest: cdbe16b11766f10e1f51c89a3d3ad100

Returns the previous sibling in the document tree. Changing the returned node will also change the node in the document tree.

For example, if you have XML like this:

.. literalinclude:: ../../../snippets/qtbase-src-xml-doc-snippets-code-src_xml_dom_qdom.py
    :lines: 109-111

and this :sip:ref:`~PyQt5.QtXml.QDomNode` represents the &lt;p&gt; tag,  will return the node representing the &lt;h1&gt; tag.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QDomNode.nextSibling`.
