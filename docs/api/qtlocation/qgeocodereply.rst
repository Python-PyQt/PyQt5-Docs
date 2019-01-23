:orphan:

.. sip:class:: PyQt5.QtLocation.QGeoCodeReply
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtLocation/QGeoCodeReply-c.rst

    .. sip:enum:: PyQt5.QtLocation.QGeoCodeReply.Error
        :description: QtLocation/QGeoCodeReply-Error-e.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoCodeReply.Error.CombinationError
            :description: QtLocation/QGeoCodeReply-Error-CombinationError-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoCodeReply.Error.CommunicationError
            :description: QtLocation/QGeoCodeReply-Error-CommunicationError-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoCodeReply.Error.EngineNotSetError
            :description: QtLocation/QGeoCodeReply-Error-EngineNotSetError-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoCodeReply.Error.NoError
            :description: QtLocation/QGeoCodeReply-Error-NoError-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoCodeReply.Error.ParseError
            :description: QtLocation/QGeoCodeReply-Error-ParseError-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoCodeReply.Error.UnknownError
            :description: QtLocation/QGeoCodeReply-Error-UnknownError-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoCodeReply.Error.UnsupportedOptionError
            :description: QtLocation/QGeoCodeReply-Error-UnsupportedOptionError-v.rst

    .. sip:method:: PyQt5.QtLocation.QGeoCodeReply.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtLocation/QGeoCodeReply-__init__-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoCodeReply.__init__
        :args:
            :sip:ref:`~PyQt5.QtLocation.QGeoCodeReply.Error`
            str
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtLocation/QGeoCodeReply-__init__-f-1.rst

    .. sip:method:: PyQt5.QtLocation.QGeoCodeReply.abort
        :description: QtLocation/QGeoCodeReply-abort-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoCodeReply.addLocation
        :args:
            :sip:ref:`~PyQt5.QtPositioning.QGeoLocation`
        :description: QtLocation/QGeoCodeReply-addLocation-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoCodeReply.error
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QGeoCodeReply.Error`
        :description: QtLocation/QGeoCodeReply-error-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoCodeReply.errorString
        :returns:
            str
        :description: QtLocation/QGeoCodeReply-errorString-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoCodeReply.isFinished
        :returns:
            bool
        :description: QtLocation/QGeoCodeReply-isFinished-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoCodeReply.limit
        :returns:
            int
        :description: QtLocation/QGeoCodeReply-limit-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoCodeReply.locations
        :returns:
            List[:sip:ref:`~PyQt5.QtPositioning.QGeoLocation`]
        :description: QtLocation/QGeoCodeReply-locations-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoCodeReply.offset
        :returns:
            int
        :description: QtLocation/QGeoCodeReply-offset-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoCodeReply.setError
        :args:
            :sip:ref:`~PyQt5.QtLocation.QGeoCodeReply.Error`
            str
        :description: QtLocation/QGeoCodeReply-setError-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoCodeReply.setFinished
        :args:
            bool
        :description: QtLocation/QGeoCodeReply-setFinished-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoCodeReply.setLimit
        :args:
            int
        :description: QtLocation/QGeoCodeReply-setLimit-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoCodeReply.setLocations
        :args:
            Iterable[:sip:ref:`~PyQt5.QtPositioning.QGeoLocation`]
        :description: QtLocation/QGeoCodeReply-setLocations-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoCodeReply.setOffset
        :args:
            int
        :description: QtLocation/QGeoCodeReply-setOffset-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoCodeReply.setViewport
        :args:
            :sip:ref:`~PyQt5.QtPositioning.QGeoShape`
        :description: QtLocation/QGeoCodeReply-setViewport-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoCodeReply.viewport
        :returns:
            :sip:ref:`~PyQt5.QtPositioning.QGeoShape`
        :description: QtLocation/QGeoCodeReply-viewport-f.rst

    .. sip:signal:: PyQt5.QtLocation.QGeoCodeReply.aborted
        :description: QtLocation/QGeoCodeReply-aborted-s.rst

    .. sip:signal:: PyQt5.QtLocation.QGeoCodeReply.error
        :description: QtLocation/QGeoCodeReply-error-f-1.rst

    .. sip:signal:: PyQt5.QtLocation.QGeoCodeReply.error
        :args:
            :sip:ref:`~PyQt5.QtLocation.QGeoCodeReply.Error`
            errorString: str = ''
        :description: QtLocation/QGeoCodeReply-error-f-2.rst

    .. sip:signal:: PyQt5.QtLocation.QGeoCodeReply.finished
        :description: QtLocation/QGeoCodeReply-finished-s.rst
