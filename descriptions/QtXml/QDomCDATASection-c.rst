.. sip:class-description::
    :status: todo
    :brief: Represents an XML CDATA section
    :digest: 439a5e671976006358c0cb3fb1500c48

The :sip:ref:`~PyQt5.QtXml.QDomCDATASection` class represents an XML CDATA section.

CDATA sections are used to escape blocks of text containing characters that would otherwise be regarded as markup. The only delimiter that is recognized in a CDATA section is the "]]&gt;" string that terminates the CDATA section. CDATA sections cannot be nested. Their primary purpose is for including material such as XML fragments, without needing to escape all the delimiters.

Adjacent :sip:ref:`~PyQt5.QtXml.QDomCDATASection` nodes are not merged by the :sip:ref:`~PyQt5.QtXml.QDomNode.normalize` function.

For further information about the Document Object Model see http://www.w3.org/TR/REC-DOM-Level-1/ and http://www.w3.org/TR/DOM-Level-2-Core/. For a more general introduction of the DOM implementation see the :sip:ref:`~PyQt5.QtXml.QDomDocument` documentation.
