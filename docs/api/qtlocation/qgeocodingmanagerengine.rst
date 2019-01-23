:orphan:

.. sip:class:: PyQt5.QtLocation.QGeoCodingManagerEngine
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtLocation/QGeoCodingManagerEngine-c.rst

    .. sip:method:: PyQt5.QtLocation.QGeoCodingManagerEngine.__init__
        :args:
            Dict[str, Any]
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtLocation/QGeoCodingManagerEngine-__init__-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoCodingManagerEngine.geocode
        :args:
            :sip:ref:`~PyQt5.QtPositioning.QGeoAddress`
            :sip:ref:`~PyQt5.QtPositioning.QGeoShape`
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QGeoCodeReply`
        :description: QtLocation/QGeoCodingManagerEngine-geocode-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoCodingManagerEngine.geocode
        :args:
            str
            int
            int
            :sip:ref:`~PyQt5.QtPositioning.QGeoShape`
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QGeoCodeReply`
        :description: QtLocation/QGeoCodingManagerEngine-geocode-f-1.rst

    .. sip:method:: PyQt5.QtLocation.QGeoCodingManagerEngine.locale
        :returns:
            :sip:ref:`~PyQt5.QtCore.QLocale`
        :description: QtLocation/QGeoCodingManagerEngine-locale-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoCodingManagerEngine.managerName
        :returns:
            str
        :description: QtLocation/QGeoCodingManagerEngine-managerName-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoCodingManagerEngine.managerVersion
        :returns:
            int
        :description: QtLocation/QGeoCodingManagerEngine-managerVersion-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoCodingManagerEngine.reverseGeocode
        :args:
            :sip:ref:`~PyQt5.QtPositioning.QGeoCoordinate`
            :sip:ref:`~PyQt5.QtPositioning.QGeoShape`
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QGeoCodeReply`
        :description: QtLocation/QGeoCodingManagerEngine-reverseGeocode-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoCodingManagerEngine.setLocale
        :args:
            :sip:ref:`~PyQt5.QtCore.QLocale`
        :description: QtLocation/QGeoCodingManagerEngine-setLocale-f.rst

    .. sip:signal:: PyQt5.QtLocation.QGeoCodingManagerEngine.error
        :args:
            :sip:ref:`~PyQt5.QtLocation.QGeoCodeReply`
            :sip:ref:`~PyQt5.QtLocation.QGeoCodeReply.Error`
            errorString: str = ''
        :description: QtLocation/QGeoCodingManagerEngine-error-s.rst

    .. sip:signal:: PyQt5.QtLocation.QGeoCodingManagerEngine.finished
        :args:
            :sip:ref:`~PyQt5.QtLocation.QGeoCodeReply`
        :description: QtLocation/QGeoCodingManagerEngine-finished-s.rst
