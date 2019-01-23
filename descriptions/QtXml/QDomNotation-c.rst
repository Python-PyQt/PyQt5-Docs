.. sip:class-description::
    :status: todo
    :brief: Represents an XML notation
    :digest: 8e18a8038ef53f2e7f50498a4ae8e8c4

The :sip:ref:`~PyQt5.QtXml.QDomNotation` class represents an XML notation.

A notation either declares, by name, the format of an unparsed entity (see section 4.7 of the XML 1.0 specification), or is used for formal declaration of processing instruction targets (see section 2.6 of the XML 1.0 specification).

DOM does not support editing notation nodes; they are therefore read-only.

A notation node does not have any parent.

You can retrieve the :sip:ref:`~PyQt5.QtXml.QDomNotation.publicId` and :sip:ref:`~PyQt5.QtXml.QDomNotation.systemId` from a notation node.

For further information about the Document Object Model see Level 1 and Level 2 Core. For a more general introduction of the DOM implementation see the :sip:ref:`~PyQt5.QtXml.QDomDocument` documentation.
