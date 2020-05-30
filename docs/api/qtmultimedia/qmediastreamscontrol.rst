:orphan:

.. sip:class:: PyQt5.QtMultimedia.QMediaStreamsControl
    :inherits: :sip:ref:`~PyQt5.QtMultimedia.QMediaControl`
    :description: QtMultimedia/QMediaStreamsControl-c.rst

    .. sip:enum:: PyQt5.QtMultimedia.QMediaStreamsControl.StreamType
        :description: QtMultimedia/QMediaStreamsControl-StreamType-e.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaStreamsControl.StreamType.AudioStream
            :description: QtMultimedia/QMediaStreamsControl-StreamType-AudioStream-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaStreamsControl.StreamType.DataStream
            :description: QtMultimedia/QMediaStreamsControl-StreamType-DataStream-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaStreamsControl.StreamType.SubPictureStream
            :description: QtMultimedia/QMediaStreamsControl-StreamType-SubPictureStream-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaStreamsControl.StreamType.UnknownStream
            :description: QtMultimedia/QMediaStreamsControl-StreamType-UnknownStream-v.rst

        .. sip:enum-member:: PyQt5.QtMultimedia.QMediaStreamsControl.StreamType.VideoStream
            :description: QtMultimedia/QMediaStreamsControl-StreamType-VideoStream-v.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaStreamsControl.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtMultimedia/QMediaStreamsControl-__init__-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaStreamsControl.isActive
        :args:
            int
        :returns:
            bool
        :description: QtMultimedia/QMediaStreamsControl-isActive-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaStreamsControl.metaData
        :args:
            int
            str
        :returns:
            Any
        :description: QtMultimedia/QMediaStreamsControl-metaData-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaStreamsControl.setActive
        :args:
            int
            bool
        :description: QtMultimedia/QMediaStreamsControl-setActive-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaStreamsControl.streamCount
        :returns:
            int
        :description: QtMultimedia/QMediaStreamsControl-streamCount-f.rst

    .. sip:method:: PyQt5.QtMultimedia.QMediaStreamsControl.streamType
        :args:
            int
        :returns:
            :sip:ref:`~PyQt5.QtMultimedia.QMediaStreamsControl.StreamType`
        :description: QtMultimedia/QMediaStreamsControl-streamType-f.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaStreamsControl.activeStreamsChanged
        :description: QtMultimedia/QMediaStreamsControl-activeStreamsChanged-s.rst

    .. sip:signal:: PyQt5.QtMultimedia.QMediaStreamsControl.streamsChanged
        :description: QtMultimedia/QMediaStreamsControl-streamsChanged-s.rst
