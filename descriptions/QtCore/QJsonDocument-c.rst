.. sip:class-description::
    :status: todo
    :brief: Way to read and write JSON documents
    :digest: ea8950b65510cb1daf6b323ac229f6d2

The :sip:ref:`~PyQt5.QtCore.QJsonDocument` class provides a way to read and write JSON documents.

:sip:ref:`~PyQt5.QtCore.QJsonDocument` is a class that wraps a complete JSON document and can read and write this document both from a UTF-8 encoded text based representation as well as Qt's own binary format.

A JSON document can be converted from its text-based representation to a :sip:ref:`~PyQt5.QtCore.QJsonDocument` using QJsonDocument::fromJson(). :sip:ref:`~PyQt5.QtCore.QJsonDocument.toJson` converts it back to text. The parser is very fast and efficient and converts the JSON to the binary representation used by Qt.

Validity of the parsed document can be queried with !\ :sip:ref:`~PyQt5.QtCore.QJsonDocument.isNull`

A document can be queried as to whether it contains an array or an object using :sip:ref:`~PyQt5.QtCore.QJsonDocument.isArray` and :sip:ref:`~PyQt5.QtCore.QJsonDocument.isObject`. The array or object contained in the document can be retrieved using :sip:ref:`~PyQt5.QtCore.QJsonDocument.array` or :sip:ref:`~PyQt5.QtCore.QJsonDocument.object` and then read or manipulated.

A document can also be created from a stored binary representation using :sip:ref:`~PyQt5.QtCore.QJsonDocument.fromBinaryData` or :sip:ref:`~PyQt5.QtCore.QJsonDocument.fromRawData`.

.. seealso:: `JSON Support in Qt <https://doc.qt.io/qt-5/json.html>`_, `JSON Save Game Example <https://doc.qt.io/qt-5/qtcore-serialization-savegame-example.html>`_.
