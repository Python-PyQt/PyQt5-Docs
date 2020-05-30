:orphan:

.. sip:class:: PyQt5.QtHelp.QHelpEngineCore
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtHelp/QHelpEngineCore-c.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.__init__
        :args:
            str
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtHelp/QHelpEngineCore-__init__-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.addCustomFilter
        :args:
            str
            Iterable[str]
        :returns:
            bool
        :description: QtHelp/QHelpEngineCore-addCustomFilter-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.autoSaveFilter
        :returns:
            bool
        :description: QtHelp/QHelpEngineCore-autoSaveFilter-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.collectionFile
        :returns:
            str
        :description: QtHelp/QHelpEngineCore-collectionFile-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.copyCollectionFile
        :args:
            str
        :returns:
            bool
        :description: QtHelp/QHelpEngineCore-copyCollectionFile-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.currentFilter
        :returns:
            str
        :description: QtHelp/QHelpEngineCore-currentFilter-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.customFilters
        :returns:
            List[str]
        :description: QtHelp/QHelpEngineCore-customFilters-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.customValue
        :args:
            str
            defaultValue: Any = None
        :returns:
            Any
        :description: QtHelp/QHelpEngineCore-customValue-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.documentationFileName
        :args:
            str
        :returns:
            str
        :description: QtHelp/QHelpEngineCore-documentationFileName-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.documentsForIdentifier
        :args:
            str
        :returns:
            List[:sip:ref:`~PyQt5.QtHelp.QHelpLink`]
        :description: QtHelp/QHelpEngineCore-documentsForIdentifier-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.documentsForIdentifier
        :args:
            str
            str
        :returns:
            List[:sip:ref:`~PyQt5.QtHelp.QHelpLink`]
        :description: QtHelp/QHelpEngineCore-documentsForIdentifier-f-1.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.documentsForKeyword
        :args:
            str
        :returns:
            List[:sip:ref:`~PyQt5.QtHelp.QHelpLink`]
        :description: QtHelp/QHelpEngineCore-documentsForKeyword-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.documentsForKeyword
        :args:
            str
            str
        :returns:
            List[:sip:ref:`~PyQt5.QtHelp.QHelpLink`]
        :description: QtHelp/QHelpEngineCore-documentsForKeyword-f-1.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.error
        :returns:
            str
        :description: QtHelp/QHelpEngineCore-error-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.fileData
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QByteArray`
        :description: QtHelp/QHelpEngineCore-fileData-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.files
        :args:
            str
            Iterable[str]
            extensionFilter: str = ''
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QUrl`]
        :description: QtHelp/QHelpEngineCore-files-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.files
        :args:
            str
            str
            extensionFilter: str = ''
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QUrl`]
        :description: QtHelp/QHelpEngineCore-files-f-1.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.filterAttributes
        :returns:
            List[str]
        :description: QtHelp/QHelpEngineCore-filterAttributes-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.filterAttributes
        :args:
            str
        :returns:
            List[str]
        :description: QtHelp/QHelpEngineCore-filterAttributes-f-1.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.filterAttributeSets
        :args:
            str
        :returns:
            List[List[str]]
        :description: QtHelp/QHelpEngineCore-filterAttributeSets-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.filterEngine
        :returns:
            :sip:ref:`~PyQt5.QtHelp.QHelpFilterEngine`
        :description: QtHelp/QHelpEngineCore-filterEngine-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.findFile
        :args:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtHelp/QHelpEngineCore-findFile-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.linksForIdentifier
        :args:
            str
        :returns:
            Dict[str, :sip:ref:`~PyQt5.QtCore.QUrl`]
        :description: QtHelp/QHelpEngineCore-linksForIdentifier-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.linksForKeyword
        :args:
            str
        :returns:
            Dict[str, :sip:ref:`~PyQt5.QtCore.QUrl`]
        :description: QtHelp/QHelpEngineCore-linksForKeyword-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.metaData
        :args:
            str
            str
        :returns:
            Any
        :static:
        :description: QtHelp/QHelpEngineCore-metaData-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.namespaceName
        :args:
            str
        :returns:
            str
        :static:
        :description: QtHelp/QHelpEngineCore-namespaceName-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.registerDocumentation
        :args:
            str
        :returns:
            bool
        :description: QtHelp/QHelpEngineCore-registerDocumentation-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.registeredDocumentations
        :returns:
            List[str]
        :description: QtHelp/QHelpEngineCore-registeredDocumentations-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.removeCustomFilter
        :args:
            str
        :returns:
            bool
        :description: QtHelp/QHelpEngineCore-removeCustomFilter-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.removeCustomValue
        :args:
            str
        :returns:
            bool
        :description: QtHelp/QHelpEngineCore-removeCustomValue-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.setAutoSaveFilter
        :args:
            bool
        :description: QtHelp/QHelpEngineCore-setAutoSaveFilter-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.setCollectionFile
        :args:
            str
        :description: QtHelp/QHelpEngineCore-setCollectionFile-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.setCurrentFilter
        :args:
            str
        :description: QtHelp/QHelpEngineCore-setCurrentFilter-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.setCustomValue
        :args:
            str
            Any
        :returns:
            bool
        :description: QtHelp/QHelpEngineCore-setCustomValue-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.setupData
        :returns:
            bool
        :description: QtHelp/QHelpEngineCore-setupData-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.setUsesFilterEngine
        :args:
            bool
        :description: QtHelp/QHelpEngineCore-setUsesFilterEngine-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.unregisterDocumentation
        :args:
            str
        :returns:
            bool
        :description: QtHelp/QHelpEngineCore-unregisterDocumentation-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpEngineCore.usesFilterEngine
        :returns:
            bool
        :description: QtHelp/QHelpEngineCore-usesFilterEngine-f.rst

    .. sip:signal:: PyQt5.QtHelp.QHelpEngineCore.currentFilterChanged
        :args:
            str
        :description: QtHelp/QHelpEngineCore-currentFilterChanged-s.rst

    .. sip:signal:: PyQt5.QtHelp.QHelpEngineCore.readersAboutToBeInvalidated
        :description: QtHelp/QHelpEngineCore-readersAboutToBeInvalidated-s.rst

    .. sip:signal:: PyQt5.QtHelp.QHelpEngineCore.setupFinished
        :description: QtHelp/QHelpEngineCore-setupFinished-s.rst

    .. sip:signal:: PyQt5.QtHelp.QHelpEngineCore.setupStarted
        :description: QtHelp/QHelpEngineCore-setupStarted-s.rst

    .. sip:signal:: PyQt5.QtHelp.QHelpEngineCore.warning
        :args:
            str
        :description: QtHelp/QHelpEngineCore-warning-s.rst
