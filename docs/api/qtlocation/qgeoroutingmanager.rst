:orphan:

.. sip:class:: PyQt5.QtLocation.QGeoRoutingManager
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtLocation/QGeoRoutingManager-c.rst

    .. sip:method:: PyQt5.QtLocation.QGeoRoutingManager.calculateRoute
        :args:
            :sip:ref:`~PyQt5.QtLocation.QGeoRouteRequest`
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QGeoRouteReply`
        :description: QtLocation/QGeoRoutingManager-calculateRoute-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoRoutingManager.locale
        :returns:
            :sip:ref:`~PyQt5.QtCore.QLocale`
        :description: QtLocation/QGeoRoutingManager-locale-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoRoutingManager.managerName
        :returns:
            str
        :description: QtLocation/QGeoRoutingManager-managerName-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoRoutingManager.managerVersion
        :returns:
            int
        :description: QtLocation/QGeoRoutingManager-managerVersion-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoRoutingManager.measurementSystem
        :returns:
            :sip:ref:`~PyQt5.QtCore.QLocale.MeasurementSystem`
        :description: QtLocation/QGeoRoutingManager-measurementSystem-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoRoutingManager.setLocale
        :args:
            :sip:ref:`~PyQt5.QtCore.QLocale`
        :description: QtLocation/QGeoRoutingManager-setLocale-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoRoutingManager.setMeasurementSystem
        :args:
            :sip:ref:`~PyQt5.QtCore.QLocale.MeasurementSystem`
        :description: QtLocation/QGeoRoutingManager-setMeasurementSystem-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoRoutingManager.supportedFeatureTypes
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QGeoRouteRequest.FeatureTypes`
        :description: QtLocation/QGeoRoutingManager-supportedFeatureTypes-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoRoutingManager.supportedFeatureWeights
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QGeoRouteRequest.FeatureWeights`
        :description: QtLocation/QGeoRoutingManager-supportedFeatureWeights-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoRoutingManager.supportedManeuverDetails
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QGeoRouteRequest.ManeuverDetails`
        :description: QtLocation/QGeoRoutingManager-supportedManeuverDetails-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoRoutingManager.supportedRouteOptimizations
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QGeoRouteRequest.RouteOptimizations`
        :description: QtLocation/QGeoRoutingManager-supportedRouteOptimizations-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoRoutingManager.supportedSegmentDetails
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QGeoRouteRequest.SegmentDetails`
        :description: QtLocation/QGeoRoutingManager-supportedSegmentDetails-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoRoutingManager.supportedTravelModes
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QGeoRouteRequest.TravelModes`
        :description: QtLocation/QGeoRoutingManager-supportedTravelModes-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoRoutingManager.updateRoute
        :args:
            :sip:ref:`~PyQt5.QtLocation.QGeoRoute`
            :sip:ref:`~PyQt5.QtPositioning.QGeoCoordinate`
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QGeoRouteReply`
        :description: QtLocation/QGeoRoutingManager-updateRoute-f.rst

    .. sip:signal:: PyQt5.QtLocation.QGeoRoutingManager.error
        :args:
            :sip:ref:`~PyQt5.QtLocation.QGeoRouteReply`
            :sip:ref:`~PyQt5.QtLocation.QGeoRouteReply.Error`
            errorString: str = ''
        :description: QtLocation/QGeoRoutingManager-error-s.rst

    .. sip:signal:: PyQt5.QtLocation.QGeoRoutingManager.finished
        :args:
            :sip:ref:`~PyQt5.QtLocation.QGeoRouteReply`
        :description: QtLocation/QGeoRoutingManager-finished-s.rst
