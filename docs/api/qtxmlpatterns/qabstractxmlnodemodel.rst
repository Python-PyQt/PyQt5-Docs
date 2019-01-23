:orphan:

.. sip:class:: PyQt5.QtXmlPatterns.QAbstractXmlNodeModel
    :description: QtXmlPatterns/QAbstractXmlNodeModel-c.rst

    .. sip:enum:: PyQt5.QtXmlPatterns.QAbstractXmlNodeModel.SimpleAxis
        :description: QtXmlPatterns/QAbstractXmlNodeModel-SimpleAxis-e.rst

        .. sip:enum-member:: PyQt5.QtXmlPatterns.QAbstractXmlNodeModel.SimpleAxis.FirstChild
            :description: QtXmlPatterns/QAbstractXmlNodeModel-SimpleAxis-FirstChild-v.rst

        .. sip:enum-member:: PyQt5.QtXmlPatterns.QAbstractXmlNodeModel.SimpleAxis.NextSibling
            :description: QtXmlPatterns/QAbstractXmlNodeModel-SimpleAxis-NextSibling-v.rst

        .. sip:enum-member:: PyQt5.QtXmlPatterns.QAbstractXmlNodeModel.SimpleAxis.Parent
            :description: QtXmlPatterns/QAbstractXmlNodeModel-SimpleAxis-Parent-v.rst

        .. sip:enum-member:: PyQt5.QtXmlPatterns.QAbstractXmlNodeModel.SimpleAxis.PreviousSibling
            :description: QtXmlPatterns/QAbstractXmlNodeModel-SimpleAxis-PreviousSibling-v.rst

    .. sip:method:: PyQt5.QtXmlPatterns.QAbstractXmlNodeModel.__init__
        :description: QtXmlPatterns/QAbstractXmlNodeModel-__init__-f.rst

    .. sip:method:: PyQt5.QtXmlPatterns.QAbstractXmlNodeModel.attributes
        :args:
            :sip:ref:`~PyQt5.QtXmlPatterns.QXmlNodeModelIndex`
        :returns:
            List[:sip:ref:`~PyQt5.QtXmlPatterns.QXmlNodeModelIndex`]
        :description: QtXmlPatterns/QAbstractXmlNodeModel-attributes-f.rst

    .. sip:method:: PyQt5.QtXmlPatterns.QAbstractXmlNodeModel.baseUri
        :args:
            :sip:ref:`~PyQt5.QtXmlPatterns.QXmlNodeModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtXmlPatterns/QAbstractXmlNodeModel-baseUri-f.rst

    .. sip:method:: PyQt5.QtXmlPatterns.QAbstractXmlNodeModel.compareOrder
        :args:
            :sip:ref:`~PyQt5.QtXmlPatterns.QXmlNodeModelIndex`
            :sip:ref:`~PyQt5.QtXmlPatterns.QXmlNodeModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtXmlPatterns.QXmlNodeModelIndex.DocumentOrder`
        :description: QtXmlPatterns/QAbstractXmlNodeModel-compareOrder-f.rst

    .. sip:method:: PyQt5.QtXmlPatterns.QAbstractXmlNodeModel.createIndex
        :args:
            int
        :returns:
            :sip:ref:`~PyQt5.QtXmlPatterns.QXmlNodeModelIndex`
        :description: QtXmlPatterns/QAbstractXmlNodeModel-createIndex-f.rst

    .. sip:method:: PyQt5.QtXmlPatterns.QAbstractXmlNodeModel.createIndex
        :args:
            int
            int
        :returns:
            :sip:ref:`~PyQt5.QtXmlPatterns.QXmlNodeModelIndex`
        :description: QtXmlPatterns/QAbstractXmlNodeModel-createIndex-f-1.rst

    .. sip:method:: PyQt5.QtXmlPatterns.QAbstractXmlNodeModel.createIndex
        :args:
            object
            additionalData: int = 0
        :returns:
            :sip:ref:`~PyQt5.QtXmlPatterns.QXmlNodeModelIndex`
        :description: QtXmlPatterns/QAbstractXmlNodeModel-createIndex-f-2.rst

    .. sip:method:: PyQt5.QtXmlPatterns.QAbstractXmlNodeModel.documentUri
        :args:
            :sip:ref:`~PyQt5.QtXmlPatterns.QXmlNodeModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtXmlPatterns/QAbstractXmlNodeModel-documentUri-f.rst

    .. sip:method:: PyQt5.QtXmlPatterns.QAbstractXmlNodeModel.elementById
        :args:
            :sip:ref:`~PyQt5.QtXmlPatterns.QXmlName`
        :returns:
            :sip:ref:`~PyQt5.QtXmlPatterns.QXmlNodeModelIndex`
        :description: QtXmlPatterns/QAbstractXmlNodeModel-elementById-f.rst

    .. sip:method:: PyQt5.QtXmlPatterns.QAbstractXmlNodeModel.kind
        :args:
            :sip:ref:`~PyQt5.QtXmlPatterns.QXmlNodeModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtXmlPatterns.QXmlNodeModelIndex.NodeKind`
        :description: QtXmlPatterns/QAbstractXmlNodeModel-kind-f.rst

    .. sip:method:: PyQt5.QtXmlPatterns.QAbstractXmlNodeModel.name
        :args:
            :sip:ref:`~PyQt5.QtXmlPatterns.QXmlNodeModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtXmlPatterns.QXmlName`
        :description: QtXmlPatterns/QAbstractXmlNodeModel-name-f.rst

    .. sip:method:: PyQt5.QtXmlPatterns.QAbstractXmlNodeModel.namespaceBindings
        :args:
            :sip:ref:`~PyQt5.QtXmlPatterns.QXmlNodeModelIndex`
        :returns:
            List[:sip:ref:`~PyQt5.QtXmlPatterns.QXmlName`]
        :description: QtXmlPatterns/QAbstractXmlNodeModel-namespaceBindings-f.rst

    .. sip:method:: PyQt5.QtXmlPatterns.QAbstractXmlNodeModel.nextFromSimpleAxis
        :args:
            :sip:ref:`~PyQt5.QtXmlPatterns.QAbstractXmlNodeModel.SimpleAxis`
            :sip:ref:`~PyQt5.QtXmlPatterns.QXmlNodeModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtXmlPatterns.QXmlNodeModelIndex`
        :description: QtXmlPatterns/QAbstractXmlNodeModel-nextFromSimpleAxis-f.rst

    .. sip:method:: PyQt5.QtXmlPatterns.QAbstractXmlNodeModel.nodesByIdref
        :args:
            :sip:ref:`~PyQt5.QtXmlPatterns.QXmlName`
        :returns:
            List[:sip:ref:`~PyQt5.QtXmlPatterns.QXmlNodeModelIndex`]
        :description: QtXmlPatterns/QAbstractXmlNodeModel-nodesByIdref-f.rst

    .. sip:method:: PyQt5.QtXmlPatterns.QAbstractXmlNodeModel.root
        :args:
            :sip:ref:`~PyQt5.QtXmlPatterns.QXmlNodeModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtXmlPatterns.QXmlNodeModelIndex`
        :description: QtXmlPatterns/QAbstractXmlNodeModel-root-f.rst

    .. sip:method:: PyQt5.QtXmlPatterns.QAbstractXmlNodeModel.sourceLocation
        :args:
            :sip:ref:`~PyQt5.QtXmlPatterns.QXmlNodeModelIndex`
        :returns:
            :sip:ref:`~PyQt5.QtXmlPatterns.QSourceLocation`
        :description: QtXmlPatterns/QAbstractXmlNodeModel-sourceLocation-f.rst

    .. sip:method:: PyQt5.QtXmlPatterns.QAbstractXmlNodeModel.stringValue
        :args:
            :sip:ref:`~PyQt5.QtXmlPatterns.QXmlNodeModelIndex`
        :returns:
            str
        :description: QtXmlPatterns/QAbstractXmlNodeModel-stringValue-f.rst

    .. sip:method:: PyQt5.QtXmlPatterns.QAbstractXmlNodeModel.typedValue
        :args:
            :sip:ref:`~PyQt5.QtXmlPatterns.QXmlNodeModelIndex`
        :returns:
            Any
        :description: QtXmlPatterns/QAbstractXmlNodeModel-typedValue-f.rst
