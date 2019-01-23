.. sip:class-description::
    :status: todo
    :brief: Represents an XML entity
    :digest: bf479788dbfc94bbce2b2d4b9364a095

The :sip:ref:`~PyQt5.QtXml.QDomEntity` class represents an XML entity.

This class represents an entity in an XML document, either parsed or unparsed. Note that this models the entity itself not the entity declaration.

DOM does not support editing entity nodes; if a user wants to make changes to the contents of an entity, every related :sip:ref:`~PyQt5.QtXml.QDomEntityReference` node must be replaced in the DOM tree by a clone of the entity's contents, and then the desired changes must be made to each of the clones instead. All the descendants of an entity node are read-only.

An entity node does not have any parent.

You can access the entity's :sip:ref:`~PyQt5.QtXml.QDomEntity.publicId`, :sip:ref:`~PyQt5.QtXml.QDomEntity.systemId` and :sip:ref:`~PyQt5.QtXml.QDomEntity.notationName` when available.

For further information about the Document Object Model see Level 1 and Level 2 Core. For a more general introduction of the DOM implementation see the :sip:ref:`~PyQt5.QtXml.QDomDocument` documentation.
