.. sip:method-description::
    :status: todo
    :pysig: 341be97d9aff90c9978347f66f945b77
    :realsig: () const
    :digest: 5d1c1848c9cf209689c14cd262285cc4

Returns the element's text or an empty string.

Example:

.. literalinclude:: ../../../snippets/qtbase-src-xml-doc-snippets-code-src_xml_dom_qdom.py
    :lines: 173-173

The function  of the :sip:ref:`~PyQt5.QtXml.QDomElement` for the ``<h1>`` tag, will return the following text:

.. literalinclude:: ../../../snippets/qtbase-src-xml-doc-snippets-code-src_xml_dom_qdom.py
    :lines: 178-178

Comments are ignored by this function. It only evaluates :sip:ref:`~PyQt5.QtXml.QDomText` and :sip:ref:`~PyQt5.QtXml.QDomCDATASection` objects.
