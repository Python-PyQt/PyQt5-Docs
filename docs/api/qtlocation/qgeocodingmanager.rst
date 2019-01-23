:orphan:

.. sip:class:: PyQt5.QtLocation.QGeoCodingManager
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtLocation/QGeoCodingManager-c.rst

    .. sip:method:: PyQt5.QtLocation.QGeoCodingManager.geocode
        :args:
            :sip:ref:`~PyQt5.QtPositioning.QGeoAddress`
            bounds: :sip:ref:`~PyQt5.QtPositioning.QGeoShape` = QGeoShape()
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QGeoCodeReply`
        :description: QtLocation/QGeoCodingManager-geocode-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoCodingManager.geocode
        :args:
            str
            limit: int = -1
            offset: int = 0
            bounds: :sip:ref:`~PyQt5.QtPositioning.QGeoShape` = QGeoShape()
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QGeoCodeReply`
        :description: QtLocation/QGeoCodingManager-geocode-f-1.rst

    .. sip:method:: PyQt5.QtLocation.QGeoCodingManager.locale
        :returns:
            :sip:ref:`~PyQt5.QtCore.QLocale`
        :description: QtLocation/QGeoCodingManager-locale-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoCodingManager.managerName
        :returns:
            str
        :description: QtLocation/QGeoCodingManager-managerName-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoCodingManager.managerVersion
        :returns:
            int
        :description: QtLocation/QGeoCodingManager-managerVersion-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoCodingManager.reverseGeocode
        :args:
            :sip:ref:`~PyQt5.QtPositioning.QGeoCoordinate`
            bounds: :sip:ref:`~PyQt5.QtPositioning.QGeoShape` = QGeoShape()
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QGeoCodeReply`
        :description: QtLocation/QGeoCodingManager-reverseGeocode-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoCodingManager.setLocale
        :args:
            :sip:ref:`~PyQt5.QtCore.QLocale`
        :description: QtLocation/QGeoCodingManager-setLocale-f.rst

    .. sip:signal:: PyQt5.QtLocation.QGeoCodingManager.error
        :args:
            :sip:ref:`~PyQt5.QtLocation.QGeoCodeReply`
            :sip:ref:`~PyQt5.QtLocation.QGeoCodeReply.Error`
            errorString: str = ''
        :description: QtLocation/QGeoCodingManager-error-s.rst

    .. sip:signal:: PyQt5.QtLocation.QGeoCodingManager.finished
        :args:
            :sip:ref:`~PyQt5.QtLocation.QGeoCodeReply`
        :description: QtLocation/QGeoCodingManager-finished-s.rst
