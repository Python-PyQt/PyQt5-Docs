:orphan:

.. sip:class:: PyQt5.QtLocation.QPlaceManager
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtLocation/QPlaceManager-c.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManager.category
        :args:
            str
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QPlaceCategory`
        :description: QtLocation/QPlaceManager-category-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManager.childCategories
        :args:
            parentId: str = ''
        :returns:
            List[:sip:ref:`~PyQt5.QtLocation.QPlaceCategory`]
        :description: QtLocation/QPlaceManager-childCategories-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManager.childCategoryIds
        :args:
            parentId: str = ''
        :returns:
            List[str]
        :description: QtLocation/QPlaceManager-childCategoryIds-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManager.compatiblePlace
        :args:
            :sip:ref:`~PyQt5.QtLocation.QPlace`
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QPlace`
        :description: QtLocation/QPlaceManager-compatiblePlace-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManager.getPlaceContent
        :args:
            :sip:ref:`~PyQt5.QtLocation.QPlaceContentRequest`
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QPlaceContentReply`
        :description: QtLocation/QPlaceManager-getPlaceContent-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManager.getPlaceDetails
        :args:
            str
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QPlaceDetailsReply`
        :description: QtLocation/QPlaceManager-getPlaceDetails-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManager.initializeCategories
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QPlaceReply`
        :description: QtLocation/QPlaceManager-initializeCategories-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManager.locales
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QLocale`]
        :description: QtLocation/QPlaceManager-locales-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManager.managerName
        :returns:
            str
        :description: QtLocation/QPlaceManager-managerName-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManager.managerVersion
        :returns:
            int
        :description: QtLocation/QPlaceManager-managerVersion-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManager.matchingPlaces
        :args:
            :sip:ref:`~PyQt5.QtLocation.QPlaceMatchRequest`
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QPlaceMatchReply`
        :description: QtLocation/QPlaceManager-matchingPlaces-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManager.parentCategoryId
        :args:
            str
        :returns:
            str
        :description: QtLocation/QPlaceManager-parentCategoryId-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManager.removeCategory
        :args:
            str
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QPlaceIdReply`
        :description: QtLocation/QPlaceManager-removeCategory-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManager.removePlace
        :args:
            str
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QPlaceIdReply`
        :description: QtLocation/QPlaceManager-removePlace-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManager.saveCategory
        :args:
            :sip:ref:`~PyQt5.QtLocation.QPlaceCategory`
            parentId: str = ''
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QPlaceIdReply`
        :description: QtLocation/QPlaceManager-saveCategory-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManager.savePlace
        :args:
            :sip:ref:`~PyQt5.QtLocation.QPlace`
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QPlaceIdReply`
        :description: QtLocation/QPlaceManager-savePlace-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManager.search
        :args:
            :sip:ref:`~PyQt5.QtLocation.QPlaceSearchRequest`
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QPlaceSearchReply`
        :description: QtLocation/QPlaceManager-search-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManager.searchSuggestions
        :args:
            :sip:ref:`~PyQt5.QtLocation.QPlaceSearchRequest`
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QPlaceSearchSuggestionReply`
        :description: QtLocation/QPlaceManager-searchSuggestions-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManager.setLocale
        :args:
            :sip:ref:`~PyQt5.QtCore.QLocale`
        :description: QtLocation/QPlaceManager-setLocale-f.rst

    .. sip:method:: PyQt5.QtLocation.QPlaceManager.setLocales
        :args:
            Iterable[:sip:ref:`~PyQt5.QtCore.QLocale`]
        :description: QtLocation/QPlaceManager-setLocales-f.rst

    .. sip:signal:: PyQt5.QtLocation.QPlaceManager.categoryAdded
        :args:
            :sip:ref:`~PyQt5.QtLocation.QPlaceCategory`
            str
        :description: QtLocation/QPlaceManager-categoryAdded-s.rst

    .. sip:signal:: PyQt5.QtLocation.QPlaceManager.categoryRemoved
        :args:
            str
            str
        :description: QtLocation/QPlaceManager-categoryRemoved-s.rst

    .. sip:signal:: PyQt5.QtLocation.QPlaceManager.categoryUpdated
        :args:
            :sip:ref:`~PyQt5.QtLocation.QPlaceCategory`
            str
        :description: QtLocation/QPlaceManager-categoryUpdated-s.rst

    .. sip:signal:: PyQt5.QtLocation.QPlaceManager.dataChanged
        :description: QtLocation/QPlaceManager-dataChanged-s.rst

    .. sip:signal:: PyQt5.QtLocation.QPlaceManager.error
        :args:
            :sip:ref:`~PyQt5.QtLocation.QPlaceReply`
            :sip:ref:`~PyQt5.QtLocation.QPlaceReply.Error`
            errorString: str = ''
        :description: QtLocation/QPlaceManager-error-s.rst

    .. sip:signal:: PyQt5.QtLocation.QPlaceManager.finished
        :args:
            :sip:ref:`~PyQt5.QtLocation.QPlaceReply`
        :description: QtLocation/QPlaceManager-finished-s.rst

    .. sip:signal:: PyQt5.QtLocation.QPlaceManager.placeAdded
        :args:
            str
        :description: QtLocation/QPlaceManager-placeAdded-s.rst

    .. sip:signal:: PyQt5.QtLocation.QPlaceManager.placeRemoved
        :args:
            str
        :description: QtLocation/QPlaceManager-placeRemoved-s.rst

    .. sip:signal:: PyQt5.QtLocation.QPlaceManager.placeUpdated
        :args:
            str
        :description: QtLocation/QPlaceManager-placeUpdated-s.rst
