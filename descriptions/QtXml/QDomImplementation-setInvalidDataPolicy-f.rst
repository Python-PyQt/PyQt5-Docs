.. sip:method-description::
    :status: todo
    :pysig: 0035b58840b5f405c8f5c669567bee09
    :realsig: (QDomImplementation::InvalidDataPolicy)
    :digest: 8612b1fb938776c5eb161d9df808f189

Sets the invalid data policy, which specifies what should be done when a factory function in :sip:ref:`~PyQt5.QtXml.QDomDocument` is passed invalid data.

The *policy* is set for all instances of :sip:ref:`~PyQt5.QtXml.QDomDocument` which already exist and which will be created in the future.

.. literalinclude:: ../../../snippets/qtbase-src-xml-doc-snippets-code-src_xml_dom_qdom.py
    :lines: 54-68

.. seealso:: :sip:ref:`~PyQt5.QtXml.QDomImplementation.invalidDataPolicy`, :sip:ref:`~PyQt5.QtXml.QDomImplementation.InvalidDataPolicy.InvalidDataPolicy`.
