:orphan:

.. sip:class:: PyQt5.QtPositioning.QGeoAreaMonitorSource
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtPositioning/QGeoAreaMonitorSource-c.rst

    .. sip:enum:: PyQt5.QtPositioning.QGeoAreaMonitorSource.AreaMonitorFeature
        :description: QtPositioning/QGeoAreaMonitorSource-AreaMonitorFeature-e.rst

        .. sip:enum-member:: PyQt5.QtPositioning.QGeoAreaMonitorSource.AreaMonitorFeature.AnyAreaMonitorFeature
            :description: QtPositioning/QGeoAreaMonitorSource-AreaMonitorFeature-AnyAreaMonitorFeature-v.rst

        .. sip:enum-member:: PyQt5.QtPositioning.QGeoAreaMonitorSource.AreaMonitorFeature.PersistentAreaMonitorFeature
            :description: QtPositioning/QGeoAreaMonitorSource-AreaMonitorFeature-PersistentAreaMonitorFeature-v.rst

    .. sip:enum:: PyQt5.QtPositioning.QGeoAreaMonitorSource.Error
        :description: QtPositioning/QGeoAreaMonitorSource-Error-e.rst

        .. sip:enum-member:: PyQt5.QtPositioning.QGeoAreaMonitorSource.Error.AccessError
            :description: QtPositioning/QGeoAreaMonitorSource-Error-AccessError-v.rst

        .. sip:enum-member:: PyQt5.QtPositioning.QGeoAreaMonitorSource.Error.InsufficientPositionInfo
            :description: QtPositioning/QGeoAreaMonitorSource-Error-InsufficientPositionInfo-v.rst

        .. sip:enum-member:: PyQt5.QtPositioning.QGeoAreaMonitorSource.Error.NoError
            :description: QtPositioning/QGeoAreaMonitorSource-Error-NoError-v.rst

        .. sip:enum-member:: PyQt5.QtPositioning.QGeoAreaMonitorSource.Error.UnknownSourceError
            :description: QtPositioning/QGeoAreaMonitorSource-Error-UnknownSourceError-v.rst

    .. sip:method:: PyQt5.QtPositioning.QGeoAreaMonitorSource.__init__
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
        :description: QtPositioning/QGeoAreaMonitorSource-__init__-f.rst

    .. sip:method:: PyQt5.QtPositioning.QGeoAreaMonitorSource.activeMonitors
        :returns:
            List[:sip:ref:`~PyQt5.QtPositioning.QGeoAreaMonitorInfo`]
        :description: QtPositioning/QGeoAreaMonitorSource-activeMonitors-f.rst

    .. sip:method:: PyQt5.QtPositioning.QGeoAreaMonitorSource.activeMonitors
        :args:
            :sip:ref:`~PyQt5.QtPositioning.QGeoShape`
        :returns:
            List[:sip:ref:`~PyQt5.QtPositioning.QGeoAreaMonitorInfo`]
        :description: QtPositioning/QGeoAreaMonitorSource-activeMonitors-f-1.rst

    .. sip:method:: PyQt5.QtPositioning.QGeoAreaMonitorSource.availableSources
        :returns:
            List[str]
        :static:
        :description: QtPositioning/QGeoAreaMonitorSource-availableSources-f.rst

    .. sip:method:: PyQt5.QtPositioning.QGeoAreaMonitorSource.createDefaultSource
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
        :returns:
            :sip:ref:`~PyQt5.QtPositioning.QGeoAreaMonitorSource`
        :static:
        :description: QtPositioning/QGeoAreaMonitorSource-createDefaultSource-f.rst

    .. sip:method:: PyQt5.QtPositioning.QGeoAreaMonitorSource.createSource
        :args:
            str
            :sip:ref:`~PyQt5.QtCore.QObject`
        :returns:
            :sip:ref:`~PyQt5.QtPositioning.QGeoAreaMonitorSource`
        :static:
        :description: QtPositioning/QGeoAreaMonitorSource-createSource-f.rst

    .. sip:method:: PyQt5.QtPositioning.QGeoAreaMonitorSource.error
        :returns:
            :sip:ref:`~PyQt5.QtPositioning.QGeoAreaMonitorSource.Error`
        :description: QtPositioning/QGeoAreaMonitorSource-error-f.rst

    .. sip:method:: PyQt5.QtPositioning.QGeoAreaMonitorSource.positionInfoSource
        :returns:
            :sip:ref:`~PyQt5.QtPositioning.QGeoPositionInfoSource`
        :description: QtPositioning/QGeoAreaMonitorSource-positionInfoSource-f.rst

    .. sip:method:: PyQt5.QtPositioning.QGeoAreaMonitorSource.requestUpdate
        :args:
            :sip:ref:`~PyQt5.QtPositioning.QGeoAreaMonitorInfo`
            str
        :returns:
            bool
        :description: QtPositioning/QGeoAreaMonitorSource-requestUpdate-f.rst

    .. sip:method:: PyQt5.QtPositioning.QGeoAreaMonitorSource.setPositionInfoSource
        :args:
            :sip:ref:`~PyQt5.QtPositioning.QGeoPositionInfoSource`
        :description: QtPositioning/QGeoAreaMonitorSource-setPositionInfoSource-f.rst

    .. sip:method:: PyQt5.QtPositioning.QGeoAreaMonitorSource.sourceName
        :returns:
            str
        :description: QtPositioning/QGeoAreaMonitorSource-sourceName-f.rst

    .. sip:method:: PyQt5.QtPositioning.QGeoAreaMonitorSource.startMonitoring
        :args:
            :sip:ref:`~PyQt5.QtPositioning.QGeoAreaMonitorInfo`
        :returns:
            bool
        :description: QtPositioning/QGeoAreaMonitorSource-startMonitoring-f.rst

    .. sip:method:: PyQt5.QtPositioning.QGeoAreaMonitorSource.stopMonitoring
        :args:
            :sip:ref:`~PyQt5.QtPositioning.QGeoAreaMonitorInfo`
        :returns:
            bool
        :description: QtPositioning/QGeoAreaMonitorSource-stopMonitoring-f.rst

    .. sip:method:: PyQt5.QtPositioning.QGeoAreaMonitorSource.supportedAreaMonitorFeatures
        :returns:
            :sip:ref:`~PyQt5.QtPositioning.QGeoAreaMonitorSource.AreaMonitorFeatures`
        :description: QtPositioning/QGeoAreaMonitorSource-supportedAreaMonitorFeatures-f.rst

    .. sip:signal:: PyQt5.QtPositioning.QGeoAreaMonitorSource.areaEntered
        :args:
            :sip:ref:`~PyQt5.QtPositioning.QGeoAreaMonitorInfo`
            :sip:ref:`~PyQt5.QtPositioning.QGeoPositionInfo`
        :description: QtPositioning/QGeoAreaMonitorSource-areaEntered-s.rst

    .. sip:signal:: PyQt5.QtPositioning.QGeoAreaMonitorSource.areaExited
        :args:
            :sip:ref:`~PyQt5.QtPositioning.QGeoAreaMonitorInfo`
            :sip:ref:`~PyQt5.QtPositioning.QGeoPositionInfo`
        :description: QtPositioning/QGeoAreaMonitorSource-areaExited-s.rst

    .. sip:signal:: PyQt5.QtPositioning.QGeoAreaMonitorSource.error
        :description: QtPositioning/QGeoAreaMonitorSource-error-f-1.rst

    .. sip:signal:: PyQt5.QtPositioning.QGeoAreaMonitorSource.error
        :args:
            :sip:ref:`~PyQt5.QtPositioning.QGeoAreaMonitorSource.Error`
        :description: QtPositioning/QGeoAreaMonitorSource-error-f.rst

    .. sip:signal:: PyQt5.QtPositioning.QGeoAreaMonitorSource.monitorExpired
        :args:
            :sip:ref:`~PyQt5.QtPositioning.QGeoAreaMonitorInfo`
        :description: QtPositioning/QGeoAreaMonitorSource-monitorExpired-s.rst
