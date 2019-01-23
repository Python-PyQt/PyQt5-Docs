:orphan:

.. sip:class:: PyQt5.QtNetwork.QHttpMultiPart
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtNetwork/QHttpMultiPart-c.rst

    .. sip:enum:: PyQt5.QtNetwork.QHttpMultiPart.ContentType
        :description: QtNetwork/QHttpMultiPart-ContentType-e.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QHttpMultiPart.ContentType.AlternativeType
            :description: QtNetwork/QHttpMultiPart-ContentType-AlternativeType-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QHttpMultiPart.ContentType.FormDataType
            :description: QtNetwork/QHttpMultiPart-ContentType-FormDataType-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QHttpMultiPart.ContentType.MixedType
            :description: QtNetwork/QHttpMultiPart-ContentType-MixedType-v.rst

        .. sip:enum-member:: PyQt5.QtNetwork.QHttpMultiPart.ContentType.RelatedType
            :description: QtNetwork/QHttpMultiPart-ContentType-RelatedType-v.rst

    .. sip:method:: PyQt5.QtNetwork.QHttpMultiPart.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtNetwork/QHttpMultiPart-__init__-f.rst

    .. sip:method:: PyQt5.QtNetwork.QHttpMultiPart.__init__
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QHttpMultiPart.ContentType`
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtNetwork/QHttpMultiPart-__init__-f-1.rst

    .. sip:method:: PyQt5.QtNetwork.QHttpMultiPart.append
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QHttpPart`
        :description: QtNetwork/QHttpMultiPart-append-f.rst

    .. sip:method:: PyQt5.QtNetwork.QHttpMultiPart.boundary
        :returns:
            :sip:ref:`~PyQt5.QtCore.QByteArray`
        :description: QtNetwork/QHttpMultiPart-boundary-f.rst

    .. sip:method:: PyQt5.QtNetwork.QHttpMultiPart.setBoundary
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :description: QtNetwork/QHttpMultiPart-setBoundary-f.rst

    .. sip:method:: PyQt5.QtNetwork.QHttpMultiPart.setContentType
        :args:
            :sip:ref:`~PyQt5.QtNetwork.QHttpMultiPart.ContentType`
        :description: QtNetwork/QHttpMultiPart-setContentType-f.rst
