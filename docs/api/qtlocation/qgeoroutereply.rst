:orphan:

.. sip:class:: PyQt5.QtLocation.QGeoRouteReply
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtLocation/QGeoRouteReply-c.rst

    .. sip:enum:: PyQt5.QtLocation.QGeoRouteReply.Error
        :description: QtLocation/QGeoRouteReply-Error-e.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoRouteReply.Error.CommunicationError
            :description: QtLocation/QGeoRouteReply-Error-CommunicationError-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoRouteReply.Error.EngineNotSetError
            :description: QtLocation/QGeoRouteReply-Error-EngineNotSetError-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoRouteReply.Error.NoError
            :description: QtLocation/QGeoRouteReply-Error-NoError-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoRouteReply.Error.ParseError
            :description: QtLocation/QGeoRouteReply-Error-ParseError-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoRouteReply.Error.UnknownError
            :description: QtLocation/QGeoRouteReply-Error-UnknownError-v.rst

        .. sip:enum-member:: PyQt5.QtLocation.QGeoRouteReply.Error.UnsupportedOptionError
            :description: QtLocation/QGeoRouteReply-Error-UnsupportedOptionError-v.rst

    .. sip:method:: PyQt5.QtLocation.QGeoRouteReply.__init__
        :args:
            :sip:ref:`~PyQt5.QtLocation.QGeoRouteRequest`
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtLocation/QGeoRouteReply-__init__-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoRouteReply.__init__
        :args:
            :sip:ref:`~PyQt5.QtLocation.QGeoRouteReply.Error`
            str
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtLocation/QGeoRouteReply-__init__-f-1.rst

    .. sip:method:: PyQt5.QtLocation.QGeoRouteReply.abort
        :description: QtLocation/QGeoRouteReply-abort-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoRouteReply.addRoutes
        :args:
            Iterable[:sip:ref:`~PyQt5.QtLocation.QGeoRoute`]
        :description: QtLocation/QGeoRouteReply-addRoutes-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoRouteReply.error
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QGeoRouteReply.Error`
        :description: QtLocation/QGeoRouteReply-error-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoRouteReply.errorString
        :returns:
            str
        :description: QtLocation/QGeoRouteReply-errorString-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoRouteReply.isFinished
        :returns:
            bool
        :description: QtLocation/QGeoRouteReply-isFinished-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoRouteReply.request
        :returns:
            :sip:ref:`~PyQt5.QtLocation.QGeoRouteRequest`
        :description: QtLocation/QGeoRouteReply-request-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoRouteReply.routes
        :returns:
            List[:sip:ref:`~PyQt5.QtLocation.QGeoRoute`]
        :description: QtLocation/QGeoRouteReply-routes-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoRouteReply.setError
        :args:
            :sip:ref:`~PyQt5.QtLocation.QGeoRouteReply.Error`
            str
        :description: QtLocation/QGeoRouteReply-setError-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoRouteReply.setFinished
        :args:
            bool
        :description: QtLocation/QGeoRouteReply-setFinished-f.rst

    .. sip:method:: PyQt5.QtLocation.QGeoRouteReply.setRoutes
        :args:
            Iterable[:sip:ref:`~PyQt5.QtLocation.QGeoRoute`]
        :description: QtLocation/QGeoRouteReply-setRoutes-f.rst

    .. sip:signal:: PyQt5.QtLocation.QGeoRouteReply.aborted
        :description: QtLocation/QGeoRouteReply-aborted-s.rst

    .. sip:signal:: PyQt5.QtLocation.QGeoRouteReply.error
        :description: QtLocation/QGeoRouteReply-error-f-1.rst

    .. sip:signal:: PyQt5.QtLocation.QGeoRouteReply.error
        :args:
            :sip:ref:`~PyQt5.QtLocation.QGeoRouteReply.Error`
            errorString: str = ''
        :description: QtLocation/QGeoRouteReply-error-f-2.rst

    .. sip:signal:: PyQt5.QtLocation.QGeoRouteReply.finished
        :description: QtLocation/QGeoRouteReply-finished-s.rst
