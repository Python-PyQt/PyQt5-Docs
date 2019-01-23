:orphan:

.. sip:class:: PyQt5.QtHelp.QHelpSearchEngine
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtHelp/QHelpSearchEngine-c.rst

    .. sip:method:: PyQt5.QtHelp.QHelpSearchEngine.__init__
        :args:
            :sip:ref:`~PyQt5.QtHelp.QHelpEngineCore`
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtHelp/QHelpSearchEngine-__init__-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpSearchEngine.cancelIndexing
        :description: QtHelp/QHelpSearchEngine-cancelIndexing-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpSearchEngine.cancelSearching
        :description: QtHelp/QHelpSearchEngine-cancelSearching-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpSearchEngine.hitCount
        :returns:
            int
        :description: QtHelp/QHelpSearchEngine-hitCount-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpSearchEngine.hits
        :args:
            int
            int
        :returns:
            List[Tuple[str, str]]
        :description: QtHelp/QHelpSearchEngine-hits-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpSearchEngine.query
        :returns:
            List[:sip:ref:`~PyQt5.QtHelp.QHelpSearchQuery`]
        :description: QtHelp/QHelpSearchEngine-query-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpSearchEngine.queryWidget
        :returns:
            :sip:ref:`~PyQt5.QtHelp.QHelpSearchQueryWidget`
        :description: QtHelp/QHelpSearchEngine-queryWidget-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpSearchEngine.reindexDocumentation
        :description: QtHelp/QHelpSearchEngine-reindexDocumentation-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpSearchEngine.resultWidget
        :returns:
            :sip:ref:`~PyQt5.QtHelp.QHelpSearchResultWidget`
        :description: QtHelp/QHelpSearchEngine-resultWidget-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpSearchEngine.search
        :args:
            Iterable[:sip:ref:`~PyQt5.QtHelp.QHelpSearchQuery`]
        :description: QtHelp/QHelpSearchEngine-search-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpSearchEngine.search
        :args:
            str
        :description: QtHelp/QHelpSearchEngine-search-f-1.rst

    .. sip:method:: PyQt5.QtHelp.QHelpSearchEngine.searchInput
        :returns:
            str
        :description: QtHelp/QHelpSearchEngine-searchInput-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpSearchEngine.searchResultCount
        :returns:
            int
        :description: QtHelp/QHelpSearchEngine-searchResultCount-f.rst

    .. sip:method:: PyQt5.QtHelp.QHelpSearchEngine.searchResults
        :args:
            int
            int
        :returns:
            List[:sip:ref:`~PyQt5.QtHelp.QHelpSearchResult`]
        :description: QtHelp/QHelpSearchEngine-searchResults-f.rst

    .. sip:signal:: PyQt5.QtHelp.QHelpSearchEngine.indexingFinished
        :description: QtHelp/QHelpSearchEngine-indexingFinished-s.rst

    .. sip:signal:: PyQt5.QtHelp.QHelpSearchEngine.indexingStarted
        :description: QtHelp/QHelpSearchEngine-indexingStarted-s.rst

    .. sip:signal:: PyQt5.QtHelp.QHelpSearchEngine.searchingFinished
        :args:
            int
        :description: QtHelp/QHelpSearchEngine-searchingFinished-s.rst

    .. sip:signal:: PyQt5.QtHelp.QHelpSearchEngine.searchingStarted
        :description: QtHelp/QHelpSearchEngine-searchingStarted-s.rst
