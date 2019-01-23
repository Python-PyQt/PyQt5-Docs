:orphan:

.. sip:class:: PyQt5.QtCore.QJsonDocument
    :description: QtCore/QJsonDocument-c.rst

    .. sip:enum:: PyQt5.QtCore.QJsonDocument.DataValidation
        :description: QtCore/QJsonDocument-DataValidation-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QJsonDocument.DataValidation.BypassValidation
            :description: QtCore/QJsonDocument-DataValidation-BypassValidation-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QJsonDocument.DataValidation.Validate
            :description: QtCore/QJsonDocument-DataValidation-Validate-v.rst

    .. sip:enum:: PyQt5.QtCore.QJsonDocument.JsonFormat
        :description: QtCore/QJsonDocument-JsonFormat-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QJsonDocument.JsonFormat.Compact
            :description: QtCore/QJsonDocument-JsonFormat-Compact-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QJsonDocument.JsonFormat.Indented
            :description: QtCore/QJsonDocument-JsonFormat-Indented-v.rst

    .. sip:method:: PyQt5.QtCore.QJsonDocument.__init__
        :description: QtCore/QJsonDocument-__init__-f.rst

    .. sip:method:: PyQt5.QtCore.QJsonDocument.__init__
        :args:
            Dict[str, Union[:sip:ref:`~PyQt5.QtCore.QJsonValue`, :sip:ref:`~PyQt5.QtCore.QJsonValue.Type`, Iterable[:sip:ref:`~PyQt5.QtCore.QJsonValue`], bool, int, float, str]]
        :description: QtCore/QJsonDocument-__init__-f-1.rst

    .. sip:method:: PyQt5.QtCore.QJsonDocument.__init__
        :args:
            Iterable[:sip:ref:`~PyQt5.QtCore.QJsonValue`]
        :description: QtCore/QJsonDocument-__init__-f-2.rst

    .. sip:method:: PyQt5.QtCore.QJsonDocument.__init__
        :args:
            :sip:ref:`~PyQt5.QtCore.QJsonDocument`
        :description: QtCore/QJsonDocument-__init__-f-3.rst

    .. sip:method:: PyQt5.QtCore.QJsonDocument.array
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QJsonValue`]
        :description: QtCore/QJsonDocument-array-f.rst

    .. sip:method:: PyQt5.QtCore.QJsonDocument.__eq__
        :args:
            :sip:ref:`~PyQt5.QtCore.QJsonDocument`
        :returns:
            bool
        :description: QtCore/QJsonDocument-__eq__-f.rst

    .. sip:method:: PyQt5.QtCore.QJsonDocument.fromBinaryData
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
            validation: :sip:ref:`~PyQt5.QtCore.QJsonDocument.DataValidation` = :sip:ref:`~PyQt5.QtCore.QJsonDocument.DataValidation.Validate`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QJsonDocument`
        :static:
        :description: QtCore/QJsonDocument-fromBinaryData-f.rst

    .. sip:method:: PyQt5.QtCore.QJsonDocument.fromJson
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
            error: :sip:ref:`~PyQt5.QtCore.QJsonParseError` = None
        :returns:
            :sip:ref:`~PyQt5.QtCore.QJsonDocument`
        :static:
        :description: QtCore/QJsonDocument-fromJson-f.rst

    .. sip:method:: PyQt5.QtCore.QJsonDocument.fromRawData
        :args:
            str
            int
            validation: :sip:ref:`~PyQt5.QtCore.QJsonDocument.DataValidation` = :sip:ref:`~PyQt5.QtCore.QJsonDocument.DataValidation.Validate`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QJsonDocument`
        :static:
        :description: QtCore/QJsonDocument-fromRawData-f.rst

    .. sip:method:: PyQt5.QtCore.QJsonDocument.fromVariant
        :args:
            Any
        :returns:
            :sip:ref:`~PyQt5.QtCore.QJsonDocument`
        :static:
        :description: QtCore/QJsonDocument-fromVariant-f.rst

    .. sip:method:: PyQt5.QtCore.QJsonDocument.__getitem__
        :args:
            str
        :returns:
            :sip:ref:`~PyQt5.QtCore.QJsonValue`
        :description: QtCore/QJsonDocument-__getitem__-f.rst

    .. sip:method:: PyQt5.QtCore.QJsonDocument.__getitem__
        :args:
            int
        :returns:
            :sip:ref:`~PyQt5.QtCore.QJsonValue`
        :description: QtCore/QJsonDocument-__getitem__-f-1.rst

    .. sip:method:: PyQt5.QtCore.QJsonDocument.isArray
        :returns:
            bool
        :description: QtCore/QJsonDocument-isArray-f.rst

    .. sip:method:: PyQt5.QtCore.QJsonDocument.isEmpty
        :returns:
            bool
        :description: QtCore/QJsonDocument-isEmpty-f.rst

    .. sip:method:: PyQt5.QtCore.QJsonDocument.isNull
        :returns:
            bool
        :description: QtCore/QJsonDocument-isNull-f.rst

    .. sip:method:: PyQt5.QtCore.QJsonDocument.isObject
        :returns:
            bool
        :description: QtCore/QJsonDocument-isObject-f.rst

    .. sip:method:: PyQt5.QtCore.QJsonDocument.__ne__
        :args:
            :sip:ref:`~PyQt5.QtCore.QJsonDocument`
        :returns:
            bool
        :description: QtCore/QJsonDocument-__ne__-f.rst

    .. sip:method:: PyQt5.QtCore.QJsonDocument.object
        :returns:
            Dict[str, Union[:sip:ref:`~PyQt5.QtCore.QJsonValue`, :sip:ref:`~PyQt5.QtCore.QJsonValue.Type`, Iterable[:sip:ref:`~PyQt5.QtCore.QJsonValue`], bool, int, float, str]]
        :description: QtCore/QJsonDocument-object-f.rst

    .. sip:method:: PyQt5.QtCore.QJsonDocument.rawData
        :returns:
            str
            int
        :description: QtCore/QJsonDocument-rawData-f.rst

    .. sip:method:: PyQt5.QtCore.QJsonDocument.setArray
        :args:
            Iterable[:sip:ref:`~PyQt5.QtCore.QJsonValue`]
        :description: QtCore/QJsonDocument-setArray-f.rst

    .. sip:method:: PyQt5.QtCore.QJsonDocument.setObject
        :args:
            Dict[str, Union[:sip:ref:`~PyQt5.QtCore.QJsonValue`, :sip:ref:`~PyQt5.QtCore.QJsonValue.Type`, Iterable[:sip:ref:`~PyQt5.QtCore.QJsonValue`], bool, int, float, str]]
        :description: QtCore/QJsonDocument-setObject-f.rst

    .. sip:method:: PyQt5.QtCore.QJsonDocument.swap
        :args:
            :sip:ref:`~PyQt5.QtCore.QJsonDocument`
        :description: QtCore/QJsonDocument-swap-f.rst

    .. sip:method:: PyQt5.QtCore.QJsonDocument.toBinaryData
        :returns:
            :sip:ref:`~PyQt5.QtCore.QByteArray`
        :description: QtCore/QJsonDocument-toBinaryData-f.rst

    .. sip:method:: PyQt5.QtCore.QJsonDocument.toJson
        :returns:
            :sip:ref:`~PyQt5.QtCore.QByteArray`
        :description: QtCore/QJsonDocument-toJson-f.rst

    .. sip:method:: PyQt5.QtCore.QJsonDocument.toJson
        :args:
            :sip:ref:`~PyQt5.QtCore.QJsonDocument.JsonFormat`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QByteArray`
        :description: QtCore/QJsonDocument-toJson-f-1.rst

    .. sip:method:: PyQt5.QtCore.QJsonDocument.toVariant
        :returns:
            Any
        :description: QtCore/QJsonDocument-toVariant-f.rst
