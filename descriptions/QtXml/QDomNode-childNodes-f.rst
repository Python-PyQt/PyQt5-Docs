.. sip:method-description::
    :status: todo
    :pysig: a74272a95bc05f6ca7723c2e3e3b1da0
    :realsig: () const
    :digest: 79c1b14edee60e6608e0e588023c70a8

Returns a list of all direct child nodes.

Most often you will call this function on a :sip:ref:`~PyQt5.QtXml.QDomElement` object.

For example, if the XML document looks like this:

.. literalinclude:: ../../../snippets/qtbase-src-xml-doc-snippets-code-src_xml_dom_qdom.py
    :lines: 101-104

Then the list of child nodes for the "body"-element will contain the node created by the &lt;h1&gt; tag and the node created by the &lt;p&gt; tag.

The nodes in the list are not copied; so changing the nodes in the list will also change the children of this node.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QDomNode.firstChild`, :sip:ref:`~PyQt5.QtXml.QDomNode.lastChild`.
