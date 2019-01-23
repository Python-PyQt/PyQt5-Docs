:orphan:

.. sip:class:: PyQt5.QtPositioning.QGeoSatelliteInfoSource
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtPositioning/QGeoSatelliteInfoSource-c.rst

    .. sip:enum:: PyQt5.QtPositioning.QGeoSatelliteInfoSource.Error
        :description: QtPositioning/QGeoSatelliteInfoSource-Error-e.rst

        .. sip:enum-member:: PyQt5.QtPositioning.QGeoSatelliteInfoSource.Error.AccessError
            :description: QtPositioning/QGeoSatelliteInfoSource-Error-AccessError-v.rst

        .. sip:enum-member:: PyQt5.QtPositioning.QGeoSatelliteInfoSource.Error.ClosedError
            :description: QtPositioning/QGeoSatelliteInfoSource-Error-ClosedError-v.rst

        .. sip:enum-member:: PyQt5.QtPositioning.QGeoSatelliteInfoSource.Error.NoError
            :description: QtPositioning/QGeoSatelliteInfoSource-Error-NoError-v.rst

        .. sip:enum-member:: PyQt5.QtPositioning.QGeoSatelliteInfoSource.Error.UnknownSourceError
            :description: QtPositioning/QGeoSatelliteInfoSource-Error-UnknownSourceError-v.rst

    .. sip:method:: PyQt5.QtPositioning.QGeoSatelliteInfoSource.__init__
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
        :description: QtPositioning/QGeoSatelliteInfoSource-__init__-f.rst

    .. sip:method:: PyQt5.QtPositioning.QGeoSatelliteInfoSource.availableSources
        :returns:
            List[str]
        :static:
        :description: QtPositioning/QGeoSatelliteInfoSource-availableSources-f.rst

    .. sip:method:: PyQt5.QtPositioning.QGeoSatelliteInfoSource.createDefaultSource
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
        :returns:
            :sip:ref:`~PyQt5.QtPositioning.QGeoSatelliteInfoSource`
        :static:
        :description: QtPositioning/QGeoSatelliteInfoSource-createDefaultSource-f.rst

    .. sip:method:: PyQt5.QtPositioning.QGeoSatelliteInfoSource.createSource
        :args:
            str
            :sip:ref:`~PyQt5.QtCore.QObject`
        :returns:
            :sip:ref:`~PyQt5.QtPositioning.QGeoSatelliteInfoSource`
        :static:
        :description: QtPositioning/QGeoSatelliteInfoSource-createSource-f.rst

    .. sip:method:: PyQt5.QtPositioning.QGeoSatelliteInfoSource.error
        :returns:
            :sip:ref:`~PyQt5.QtPositioning.QGeoSatelliteInfoSource.Error`
        :description: QtPositioning/QGeoSatelliteInfoSource-error-f.rst

    .. sip:method:: PyQt5.QtPositioning.QGeoSatelliteInfoSource.minimumUpdateInterval
        :returns:
            int
        :description: QtPositioning/QGeoSatelliteInfoSource-minimumUpdateInterval-f.rst

    .. sip:method:: PyQt5.QtPositioning.QGeoSatelliteInfoSource.requestUpdate
        :args:
            timeout: int = 0
        :description: QtPositioning/QGeoSatelliteInfoSource-requestUpdate-f.rst

    .. sip:method:: PyQt5.QtPositioning.QGeoSatelliteInfoSource.setUpdateInterval
        :args:
            int
        :description: QtPositioning/QGeoSatelliteInfoSource-setUpdateInterval-f.rst

    .. sip:method:: PyQt5.QtPositioning.QGeoSatelliteInfoSource.sourceName
        :returns:
            str
        :description: QtPositioning/QGeoSatelliteInfoSource-sourceName-f.rst

    .. sip:method:: PyQt5.QtPositioning.QGeoSatelliteInfoSource.startUpdates
        :description: QtPositioning/QGeoSatelliteInfoSource-startUpdates-f.rst

    .. sip:method:: PyQt5.QtPositioning.QGeoSatelliteInfoSource.stopUpdates
        :description: QtPositioning/QGeoSatelliteInfoSource-stopUpdates-f.rst

    .. sip:method:: PyQt5.QtPositioning.QGeoSatelliteInfoSource.updateInterval
        :returns:
            int
        :description: QtPositioning/QGeoSatelliteInfoSource-updateInterval-f.rst

    .. sip:signal:: PyQt5.QtPositioning.QGeoSatelliteInfoSource.error
        :description: QtPositioning/QGeoSatelliteInfoSource-error-f-1.rst

    .. sip:signal:: PyQt5.QtPositioning.QGeoSatelliteInfoSource.error
        :args:
            :sip:ref:`~PyQt5.QtPositioning.QGeoSatelliteInfoSource.Error`
        :description: QtPositioning/QGeoSatelliteInfoSource-error-f.rst

    .. sip:signal:: PyQt5.QtPositioning.QGeoSatelliteInfoSource.requestTimeout
        :description: QtPositioning/QGeoSatelliteInfoSource-requestTimeout-s.rst

    .. sip:signal:: PyQt5.QtPositioning.QGeoSatelliteInfoSource.satellitesInUseUpdated
        :args:
            Iterable[:sip:ref:`~PyQt5.QtPositioning.QGeoSatelliteInfo`]
        :description: QtPositioning/QGeoSatelliteInfoSource-satellitesInUseUpdated-s.rst

    .. sip:signal:: PyQt5.QtPositioning.QGeoSatelliteInfoSource.satellitesInViewUpdated
        :args:
            Iterable[:sip:ref:`~PyQt5.QtPositioning.QGeoSatelliteInfo`]
        :description: QtPositioning/QGeoSatelliteInfoSource-satellitesInViewUpdated-s.rst
