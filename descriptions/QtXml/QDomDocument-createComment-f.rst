.. sip:method-description::
    :status: todo
    :pysig: 3c05476aa96118d32f09600a7991fa28
    :realsig: (const QString&)
    :digest: 6a95e61859e3868a9c0f45c290230c97

Creates a new comment for the string *value* that can be inserted into the document, e.g. using :sip:ref:`~PyQt5.QtXml.QDomNode.appendChild`.

If *value* contains characters which cannot be stored in an XML comment, the behavior of this function is governed by :sip:ref:`~PyQt5.QtXml.QDomImplementation.InvalidDataPolicy`.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QDomNode.appendChild`, :sip:ref:`~PyQt5.QtXml.QDomNode.insertBefore`, :sip:ref:`~PyQt5.QtXml.QDomNode.insertAfter`.
