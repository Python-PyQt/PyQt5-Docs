.. sip:class-description::
    :status: todo
    :brief: Information about the features of the DOM implementation
    :digest: 27a5dce148d2e880c61aeb6c80b613d2

The :sip:ref:`~PyQt5.QtXml.QDomImplementation` class provides information about the features of the DOM implementation.

This class describes the features that are supported by the DOM implementation. Currently the XML subset of DOM Level 1 and DOM Level 2 Core are supported.

Normally you will use the function :sip:ref:`~PyQt5.QtXml.QDomDocument.implementation` to get the implementation object.

You can create a new document type with :sip:ref:`~PyQt5.QtXml.QDomImplementation.createDocumentType` and a new document with :sip:ref:`~PyQt5.QtXml.QDomImplementation.createDocument`.

For further information about the Document Object Model see Level 1 and Level 2 Core. For a more general introduction of the DOM implementation see the :sip:ref:`~PyQt5.QtXml.QDomDocument` documentation.

The QDom classes have a few issues of nonconformance with the XML specifications that cannot be fixed in Qt 4 without breaking backward compatibility. The Qt XML Patterns module and the :sip:ref:`~PyQt5.QtCore.QXmlStreamReader` and :sip:ref:`~PyQt5.QtCore.QXmlStreamWriter` classes have a higher degree of a conformance.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QDomImplementation.hasFeature`.
