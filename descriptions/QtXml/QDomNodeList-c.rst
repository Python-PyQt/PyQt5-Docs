.. sip:class-description::
    :status: todo
    :brief: List of QDomNode objects
    :digest: a2e3ae063d811dc7af1f6d44189e9257

The :sip:ref:`~PyQt5.QtXml.QDomNodeList` class is a list of :sip:ref:`~PyQt5.QtXml.QDomNode` objects.

Lists can be obtained by :sip:ref:`~PyQt5.QtXml.QDomDocument.elementsByTagName` and :sip:ref:`~PyQt5.QtXml.QDomNode.childNodes`. The Document Object Model (DOM) requires these lists to be "live": whenever you change the underlying document, the contents of the list will get updated.

You can get a particular node from the list with :sip:ref:`~PyQt5.QtXml.QDomNodeList.item`. The number of items in the list is returned by :sip:ref:`~PyQt5.QtXml.QDomNodeList.length`.

For further information about the Document Object Model see Level 1 and Level 2 Core. For a more general introduction of the DOM implementation see the :sip:ref:`~PyQt5.QtXml.QDomDocument` documentation.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QDomNode.childNodes`, :sip:ref:`~PyQt5.QtXml.QDomDocument.elementsByTagName`.
