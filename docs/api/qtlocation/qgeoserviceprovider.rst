:orphan:

.. sip:class:: PyQt5.QtLocation.QGeoServiceProvider
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtLocation/QGeoServiceProvider-c.rst

    .. sip:enum:: PyQt5.QtLocation.QGeoServiceProvider.Error
        :description: QtLocation/QGeoServiceProvider-Error-e.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.Error.ConnectionError
            :description: QtLocation/QGeoServiceProvider-Error-ConnectionError-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.Error.LoaderError
            :description: QtLocation/QGeoServiceProvider-Error-LoaderError-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.Error.MissingRequiredParameterError
            :description: QtLocation/QGeoServiceProvider-Error-MissingRequiredParameterError-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.Error.NoError
            :description: QtLocation/QGeoServiceProvider-Error-NoError-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.Error.NotSupportedError
            :description: QtLocation/QGeoServiceProvider-Error-NotSupportedError-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.Error.UnknownParameterError
            :description: QtLocation/QGeoServiceProvider-Error-UnknownParameterError-v.rst

    .. sip:enum:: PyQt5.QtLocation.QGeoServiceProvider.GeocodingFeature
        :description: QtLocation/QGeoServiceProvider-GeocodingFeature-e.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.GeocodingFeature.AnyGeocodingFeatures
            :description: QtLocation/QGeoServiceProvider-GeocodingFeature-AnyGeocodingFeatures-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.GeocodingFeature.LocalizedGeocodingFeature
            :description: QtLocation/QGeoServiceProvider-GeocodingFeature-LocalizedGeocodingFeature-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.GeocodingFeature.NoGeocodingFeatures
            :description: QtLocation/QGeoServiceProvider-GeocodingFeature-NoGeocodingFeatures-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.GeocodingFeature.OfflineGeocodingFeature
            :description: QtLocation/QGeoServiceProvider-GeocodingFeature-OfflineGeocodingFeature-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.GeocodingFeature.OnlineGeocodingFeature
            :description: QtLocation/QGeoServiceProvider-GeocodingFeature-OnlineGeocodingFeature-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.GeocodingFeature.ReverseGeocodingFeature
            :description: QtLocation/QGeoServiceProvider-GeocodingFeature-ReverseGeocodingFeature-v.rst

    .. sip:enum:: PyQt5.QtLocation.QGeoServiceProvider.MappingFeature
        :description: QtLocation/QGeoServiceProvider-MappingFeature-e.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.MappingFeature.AnyMappingFeatures
            :description: QtLocation/QGeoServiceProvider-MappingFeature-AnyMappingFeatures-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.MappingFeature.LocalizedMappingFeature
            :description: QtLocation/QGeoServiceProvider-MappingFeature-LocalizedMappingFeature-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.MappingFeature.NoMappingFeatures
            :description: QtLocation/QGeoServiceProvider-MappingFeature-NoMappingFeatures-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.MappingFeature.OfflineMappingFeature
            :description: QtLocation/QGeoServiceProvider-MappingFeature-OfflineMappingFeature-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.MappingFeature.OnlineMappingFeature
            :description: QtLocation/QGeoServiceProvider-MappingFeature-OnlineMappingFeature-v.rst

    .. sip:enum:: PyQt5.QtLocation.QGeoServiceProvider.NavigationFeature
        :description: QtLocation/QGeoServiceProvider-NavigationFeature-e.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.NavigationFeature.AnyNavigationFeatures
            :description: QtLocation/QGeoServiceProvider-NavigationFeature-AnyNavigationFeatures-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.NavigationFeature.NoNavigationFeatures
            :description: QtLocation/QGeoServiceProvider-NavigationFeature-NoNavigationFeatures-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.NavigationFeature.OfflineNavigationFeature
            :description: QtLocation/QGeoServiceProvider-NavigationFeature-OfflineNavigationFeature-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.NavigationFeature.OnlineNavigationFeature
            :description: QtLocation/QGeoServiceProvider-NavigationFeature-OnlineNavigationFeature-v.rst

    .. sip:enum:: PyQt5.QtLocation.QGeoServiceProvider.PlacesFeature
        :description: QtLocation/QGeoServiceProvider-PlacesFeature-e.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.PlacesFeature.AnyPlacesFeatures
            :description: QtLocation/QGeoServiceProvider-PlacesFeature-AnyPlacesFeatures-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.PlacesFeature.LocalizedPlacesFeature
            :description: QtLocation/QGeoServiceProvider-PlacesFeature-LocalizedPlacesFeature-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.PlacesFeature.NoPlacesFeatures
            :description: QtLocation/QGeoServiceProvider-PlacesFeature-NoPlacesFeatures-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.PlacesFeature.NotificationsFeature
            :description: QtLocation/QGeoServiceProvider-PlacesFeature-NotificationsFeature-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.PlacesFeature.OfflinePlacesFeature
            :description: QtLocation/QGeoServiceProvider-PlacesFeature-OfflinePlacesFeature-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.PlacesFeature.OnlinePlacesFeature
            :description: QtLocation/QGeoServiceProvider-PlacesFeature-OnlinePlacesFeature-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.PlacesFeature.PlaceMatchingFeature
            :description: QtLocation/QGeoServiceProvider-PlacesFeature-PlaceMatchingFeature-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.PlacesFeature.PlaceRecommendationsFeature
            :description: QtLocation/QGeoServiceProvider-PlacesFeature-PlaceRecommendationsFeature-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.PlacesFeature.RemoveCategoryFeature
            :description: QtLocation/QGeoServiceProvider-PlacesFeature-RemoveCategoryFeature-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.PlacesFeature.RemovePlaceFeature
            :description: QtLocation/QGeoServiceProvider-PlacesFeature-RemovePlaceFeature-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.PlacesFeature.SaveCategoryFeature
            :description: QtLocation/QGeoServiceProvider-PlacesFeature-SaveCategoryFeature-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.PlacesFeature.SavePlaceFeature
            :description: QtLocation/QGeoServiceProvider-PlacesFeature-SavePlaceFeature-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.PlacesFeature.SearchSuggestionsFeature
            :description: QtLocation/QGeoServiceProvider-PlacesFeature-SearchSuggestionsFeature-v.rst

    .. sip:enum:: PyQt5.QtLocation.QGeoServiceProvider.RoutingFeature
        :description: QtLocation/QGeoServiceProvider-RoutingFeature-e.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.RoutingFeature.AlternativeRoutesFeature
            :description: QtLocation/QGeoServiceProvider-RoutingFeature-AlternativeRoutesFeature-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.RoutingFeature.AnyRoutingFeatures
            :description: QtLocation/QGeoServiceProvider-RoutingFeature-AnyRoutingFeatures-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.RoutingFeature.ExcludeAreasRoutingFeature
            :description: QtLocation/QGeoServiceProvider-RoutingFeature-ExcludeAreasRoutingFeature-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.RoutingFeature.LocalizedRoutingFeature
            :description: QtLocation/QGeoServiceProvider-RoutingFeature-LocalizedRoutingFeature-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.RoutingFeature.NoRoutingFeatures
            :description: QtLocation/QGeoServiceProvider-RoutingFeature-NoRoutingFeatures-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.RoutingFeature.OfflineRoutingFeature
            :description: QtLocation/QGeoServiceProvider-RoutingFeature-OfflineRoutingFeature-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.RoutingFeature.OnlineRoutingFeature
            :description: QtLocation/QGeoServiceProvider-RoutingFeature-OnlineRoutingFeature-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoServiceProvider.RoutingFeature.RouteUpdatesFeature
            :description: QtLocation/QGeoServiceProvider-RoutingFeature-RouteUpdatesFeature-v.rst

    .. sip:method:: PyQt5.QtLocation.QGeoServiceProvider.__init__
        :args:
            str
            parameters: Dict[str, Any] = {}
            allowExperimental: bool = False
        :description: QtLocation/QGeoServiceProvider-__init__-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoServiceProvider.availableServiceProviders
        :returns:
            List[str]
        :static:
        :description: QtLocation/QGeoServiceProvider-availableServiceProviders-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoServiceProvider.error
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QGeoServiceProvider.Error`
        :description: QtLocation/QGeoServiceProvider-error-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoServiceProvider.errorString
        :returns:
            str
        :description: QtLocation/QGeoServiceProvider-errorString-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoServiceProvider.geocodingError
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QGeoServiceProvider.Error`
        :description: QtLocation/QGeoServiceProvider-geocodingError-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoServiceProvider.geocodingErrorString
        :returns:
            str
        :description: QtLocation/QGeoServiceProvider-geocodingErrorString-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoServiceProvider.geocodingFeatures
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QGeoServiceProvider.GeocodingFeatures`
        :description: QtLocation/QGeoServiceProvider-geocodingFeatures-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoServiceProvider.geocodingManager
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QGeoCodingManager`
        :description: QtLocation/QGeoServiceProvider-geocodingManager-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoServiceProvider.mappingError
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QGeoServiceProvider.Error`
        :description: QtLocation/QGeoServiceProvider-mappingError-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoServiceProvider.mappingErrorString
        :returns:
            str
        :description: QtLocation/QGeoServiceProvider-mappingErrorString-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoServiceProvider.mappingFeatures
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QGeoServiceProvider.MappingFeatures`
        :description: QtLocation/QGeoServiceProvider-mappingFeatures-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoServiceProvider.navigationError
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QGeoServiceProvider.Error`
        :description: QtLocation/QGeoServiceProvider-navigationError-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoServiceProvider.navigationErrorString
        :returns:
            str
        :description: QtLocation/QGeoServiceProvider-navigationErrorString-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoServiceProvider.navigationFeatures
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QGeoServiceProvider.NavigationFeatures`
        :description: QtLocation/QGeoServiceProvider-navigationFeatures-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoServiceProvider.navigationManager
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QNavigationManager`
        :description: QtLocation/QGeoServiceProvider-navigationManager-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoServiceProvider.placeManager
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QPlaceManager`
        :description: QtLocation/QGeoServiceProvider-placeManager-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoServiceProvider.placesError
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QGeoServiceProvider.Error`
        :description: QtLocation/QGeoServiceProvider-placesError-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoServiceProvider.placesErrorString
        :returns:
            str
        :description: QtLocation/QGeoServiceProvider-placesErrorString-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoServiceProvider.placesFeatures
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QGeoServiceProvider.PlacesFeatures`
        :description: QtLocation/QGeoServiceProvider-placesFeatures-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoServiceProvider.routingError
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QGeoServiceProvider.Error`
        :description: QtLocation/QGeoServiceProvider-routingError-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoServiceProvider.routingErrorString
        :returns:
            str
        :description: QtLocation/QGeoServiceProvider-routingErrorString-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoServiceProvider.routingFeatures
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QGeoServiceProvider.RoutingFeatures`
        :description: QtLocation/QGeoServiceProvider-routingFeatures-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoServiceProvider.routingManager
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QGeoRoutingManager`
        :description: QtLocation/QGeoServiceProvider-routingManager-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoServiceProvider.setAllowExperimental
        :args:
            bool
        :description: QtLocation/QGeoServiceProvider-setAllowExperimental-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoServiceProvider.setLocale
        :args:
            :sip:ref:`~PyQt5.QtCore.QLocale`
        :description: QtLocation/QGeoServiceProvider-setLocale-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoServiceProvider.setParameters
        :args:
            Dict[str, Any]
        :description: QtLocation/QGeoServiceProvider-setParameters-f.rst
