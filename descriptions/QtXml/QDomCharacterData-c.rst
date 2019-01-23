.. sip:class-description::
    :status: todo
    :brief: Represents a generic string in the DOM
    :digest: 094dba6b1257225f4a03b48e53e07c5d

The :sip:ref:`~PyQt5.QtXml.QDomCharacterData` class represents a generic string in the DOM.

Character data as used in XML specifies a generic data string. More specialized versions of this class are :sip:ref:`~PyQt5.QtXml.QDomText`, :sip:ref:`~PyQt5.QtXml.QDomComment` and :sip:ref:`~PyQt5.QtXml.QDomCDATASection`.

The data string is set with :sip:ref:`~PyQt5.QtXml.QDomCharacterData.setData` and retrieved with :sip:ref:`~PyQt5.QtXml.QDomCharacterData.data`. You can retrieve a portion of the data string using :sip:ref:`~PyQt5.QtXml.QDomCharacterData.substringData`. Extra data can be appended with :sip:ref:`~PyQt5.QtXml.QDomCharacterData.appendData`, or inserted with :sip:ref:`~PyQt5.QtXml.QDomCharacterData.insertData`. Portions of the data string can be deleted with :sip:ref:`~PyQt5.QtXml.QDomCharacterData.deleteData` or replaced with :sip:ref:`~PyQt5.QtXml.QDomCharacterData.replaceData`. The length of the data string is returned by :sip:ref:`~PyQt5.QtXml.QDomCharacterData.length`.

The node type of the node containing this character data is returned by :sip:ref:`~PyQt5.QtXml.QDomCharacterData.nodeType`.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QDomText`, :sip:ref:`~PyQt5.QtXml.QDomComment`, :sip:ref:`~PyQt5.QtXml.QDomCDATASection`.
