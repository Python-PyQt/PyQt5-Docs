:orphan:

.. sip:class:: PyQt5.QtLocation.QPlaceManagerEngine
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtLocation/QPlaceManagerEngine-c.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManagerEngine.__init__
        :args:
            Dict[str, Any]
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtLocation/QPlaceManagerEngine-__init__-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManagerEngine.category
        :args:
            str
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QPlaceCategory`
        :description: QtLocation/QPlaceManagerEngine-category-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManagerEngine.childCategories
        :args:
            str
        :returns:
            List[:sip:ref:`~PyQt5.QtLocation.QPlaceCategory`]
        :description: QtLocation/QPlaceManagerEngine-childCategories-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManagerEngine.childCategoryIds
        :args:
            str
        :returns:
            List[str]
        :description: QtLocation/QPlaceManagerEngine-childCategoryIds-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManagerEngine.compatiblePlace
        :args:
            :sip:ref:`~PyQt5.QtLocation.QPlace`
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QPlace`
        :description: QtLocation/QPlaceManagerEngine-compatiblePlace-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManagerEngine.constructIconUrl
        :args:
            :sip:ref:`~PyQt5.QtLocation.QPlaceIcon`
            :sip:ref:`~PyQt5.QtCore.QSize`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QUrl`
        :description: QtLocation/QPlaceManagerEngine-constructIconUrl-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManagerEngine.getPlaceContent
        :args:
            :sip:ref:`~PyQt5.QtLocation.QPlaceContentRequest`
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QPlaceContentReply`
        :description: QtLocation/QPlaceManagerEngine-getPlaceContent-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManagerEngine.getPlaceDetails
        :args:
            str
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QPlaceDetailsReply`
        :description: QtLocation/QPlaceManagerEngine-getPlaceDetails-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManagerEngine.initializeCategories
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QPlaceReply`
        :description: QtLocation/QPlaceManagerEngine-initializeCategories-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManagerEngine.locales
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QLocale`]
        :description: QtLocation/QPlaceManagerEngine-locales-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManagerEngine.manager
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QPlaceManager`
        :description: QtLocation/QPlaceManagerEngine-manager-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManagerEngine.managerName
        :returns:
            str
        :description: QtLocation/QPlaceManagerEngine-managerName-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManagerEngine.managerVersion
        :returns:
            int
        :description: QtLocation/QPlaceManagerEngine-managerVersion-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManagerEngine.matchingPlaces
        :args:
            :sip:ref:`~PyQt5.QtLocation.QPlaceMatchRequest`
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QPlaceMatchReply`
        :description: QtLocation/QPlaceManagerEngine-matchingPlaces-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManagerEngine.parentCategoryId
        :args:
            str
        :returns:
            str
        :description: QtLocation/QPlaceManagerEngine-parentCategoryId-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManagerEngine.removeCategory
        :args:
            str
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QPlaceIdReply`
        :description: QtLocation/QPlaceManagerEngine-removeCategory-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManagerEngine.removePlace
        :args:
            str
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QPlaceIdReply`
        :description: QtLocation/QPlaceManagerEngine-removePlace-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManagerEngine.saveCategory
        :args:
            :sip:ref:`~PyQt5.QtLocation.QPlaceCategory`
            str
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QPlaceIdReply`
        :description: QtLocation/QPlaceManagerEngine-saveCategory-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManagerEngine.savePlace
        :args:
            :sip:ref:`~PyQt5.QtLocation.QPlace`
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QPlaceIdReply`
        :description: QtLocation/QPlaceManagerEngine-savePlace-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManagerEngine.search
        :args:
            :sip:ref:`~PyQt5.QtLocation.QPlaceSearchRequest`
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QPlaceSearchReply`
        :description: QtLocation/QPlaceManagerEngine-search-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManagerEngine.searchSuggestions
        :args:
            :sip:ref:`~PyQt5.QtLocation.QPlaceSearchRequest`
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QPlaceSearchSuggestionReply`
        :description: QtLocation/QPlaceManagerEngine-searchSuggestions-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManagerEngine.setLocales
        :args:
            Iterable[:sip:ref:`~PyQt5.QtCore.QLocale`]
        :description: QtLocation/QPlaceManagerEngine-setLocales-f.rst

    .. sip:signal:: PyQt5.QtLocation.QPlaceManagerEngine.categoryAdded
        :args:
            :sip:ref:`~PyQt5.QtLocation.QPlaceCategory`
            str
        :description: QtLocation/QPlaceManagerEngine-categoryAdded-s.rst

    .. sip:signal:: PyQt5.QtLocation.QPlaceManagerEngine.categoryRemoved
        :args:
            str
            str
        :description: QtLocation/QPlaceManagerEngine-categoryRemoved-s.rst

    .. sip:signal:: PyQt5.QtLocation.QPlaceManagerEngine.categoryUpdated
        :args:
            :sip:ref:`~PyQt5.QtLocation.QPlaceCategory`
            str
        :description: QtLocation/QPlaceManagerEngine-categoryUpdated-s.rst

    .. sip:signal:: PyQt5.QtLocation.QPlaceManagerEngine.dataChanged
        :description: QtLocation/QPlaceManagerEngine-dataChanged-s.rst

    .. sip:signal:: PyQt5.QtLocation.QPlaceManagerEngine.error
        :args:
            :sip:ref:`~PyQt5.QtLocation.QPlaceReply`
            :sip:ref:`~PyQt5.QtLocation.QPlaceReply.Error`
            errorString: str = ''
        :description: QtLocation/QPlaceManagerEngine-error-s.rst

    .. sip:signal:: PyQt5.QtLocation.QPlaceManagerEngine.finished
        :args:
            :sip:ref:`~PyQt5.QtLocation.QPlaceReply`
        :description: QtLocation/QPlaceManagerEngine-finished-s.rst

    .. sip:signal:: PyQt5.QtLocation.QPlaceManagerEngine.placeAdded
        :args:
            str
        :description: QtLocation/QPlaceManagerEngine-placeAdded-s.rst

    .. sip:signal:: PyQt5.QtLocation.QPlaceManagerEngine.placeRemoved
        :args:
            str
        :description: QtLocation/QPlaceManagerEngine-placeRemoved-s.rst

    .. sip:signal:: PyQt5.QtLocation.QPlaceManagerEngine.placeUpdated
        :args:
            str
        :description: QtLocation/QPlaceManagerEngine-placeUpdated-s.rst
