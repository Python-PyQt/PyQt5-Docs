:orphan:

.. sip:class:: PyQt5.QtGui.QScreen
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtGui/QScreen-c.rst

    .. sip:method:: PyQt5.QtGui.QScreen.angleBetween
        :args:
            :sip:ref:`~PyQt5.QtCore.Qt.ScreenOrientation`
            :sip:ref:`~PyQt5.QtCore.Qt.ScreenOrientation`
        :returns:
            int
        :description: QtGui/QScreen-angleBetween-f.rst

    .. sip:method:: PyQt5.QtGui.QScreen.availableGeometry
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRect`
        :description: QtGui/QScreen-availableGeometry-f.rst

    .. sip:method:: PyQt5.QtGui.QScreen.availableSize
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtGui/QScreen-availableSize-f.rst

    .. sip:method:: PyQt5.QtGui.QScreen.availableVirtualGeometry
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRect`
        :description: QtGui/QScreen-availableVirtualGeometry-f.rst

    .. sip:method:: PyQt5.QtGui.QScreen.availableVirtualSize
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtGui/QScreen-availableVirtualSize-f.rst

    .. sip:method:: PyQt5.QtGui.QScreen.depth
        :returns:
            int
        :description: QtGui/QScreen-depth-f.rst

    .. sip:method:: PyQt5.QtGui.QScreen.devicePixelRatio
        :returns:
            float
        :description: QtGui/QScreen-devicePixelRatio-f.rst

    .. sip:method:: PyQt5.QtGui.QScreen.geometry
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRect`
        :description: QtGui/QScreen-geometry-f.rst

    .. sip:method:: PyQt5.QtGui.QScreen.grabWindow
        :args:
            sip.voidptr
            x: int = 0
            y: int = 0
            width: int = -1
            height: int = -1
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPixmap`
        :description: QtGui/QScreen-grabWindow-f.rst

    .. sip:method:: PyQt5.QtGui.QScreen.isLandscape
        :args:
            :sip:ref:`~PyQt5.QtCore.Qt.ScreenOrientation`
        :returns:
            bool
        :description: QtGui/QScreen-isLandscape-f.rst

    .. sip:method:: PyQt5.QtGui.QScreen.isPortrait
        :args:
            :sip:ref:`~PyQt5.QtCore.Qt.ScreenOrientation`
        :returns:
            bool
        :description: QtGui/QScreen-isPortrait-f.rst

    .. sip:method:: PyQt5.QtGui.QScreen.logicalDotsPerInch
        :returns:
            float
        :description: QtGui/QScreen-logicalDotsPerInch-f.rst

    .. sip:method:: PyQt5.QtGui.QScreen.logicalDotsPerInchX
        :returns:
            float
        :description: QtGui/QScreen-logicalDotsPerInchX-f.rst

    .. sip:method:: PyQt5.QtGui.QScreen.logicalDotsPerInchY
        :returns:
            float
        :description: QtGui/QScreen-logicalDotsPerInchY-f.rst

    .. sip:method:: PyQt5.QtGui.QScreen.manufacturer
        :returns:
            str
        :description: QtGui/QScreen-manufacturer-f.rst

    .. sip:method:: PyQt5.QtGui.QScreen.mapBetween
        :args:
            :sip:ref:`~PyQt5.QtCore.Qt.ScreenOrientation`
            :sip:ref:`~PyQt5.QtCore.Qt.ScreenOrientation`
            :sip:ref:`~PyQt5.QtCore.QRect`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRect`
        :description: QtGui/QScreen-mapBetween-f.rst

    .. sip:method:: PyQt5.QtGui.QScreen.model
        :returns:
            str
        :description: QtGui/QScreen-model-f.rst

    .. sip:method:: PyQt5.QtGui.QScreen.name
        :returns:
            str
        :description: QtGui/QScreen-name-f.rst

    .. sip:method:: PyQt5.QtGui.QScreen.nativeOrientation
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.ScreenOrientation`
        :description: QtGui/QScreen-nativeOrientation-f.rst

    .. sip:method:: PyQt5.QtGui.QScreen.orientation
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.ScreenOrientation`
        :description: QtGui/QScreen-orientation-f.rst

    .. sip:method:: PyQt5.QtGui.QScreen.orientationUpdateMask
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.ScreenOrientations`
        :description: QtGui/QScreen-orientationUpdateMask-f.rst

    .. sip:method:: PyQt5.QtGui.QScreen.physicalDotsPerInch
        :returns:
            float
        :description: QtGui/QScreen-physicalDotsPerInch-f.rst

    .. sip:method:: PyQt5.QtGui.QScreen.physicalDotsPerInchX
        :returns:
            float
        :description: QtGui/QScreen-physicalDotsPerInchX-f.rst

    .. sip:method:: PyQt5.QtGui.QScreen.physicalDotsPerInchY
        :returns:
            float
        :description: QtGui/QScreen-physicalDotsPerInchY-f.rst

    .. sip:method:: PyQt5.QtGui.QScreen.physicalSize
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSizeF`
        :description: QtGui/QScreen-physicalSize-f.rst

    .. sip:method:: PyQt5.QtGui.QScreen.primaryOrientation
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.ScreenOrientation`
        :description: QtGui/QScreen-primaryOrientation-f.rst

    .. sip:method:: PyQt5.QtGui.QScreen.refreshRate
        :returns:
            float
        :description: QtGui/QScreen-refreshRate-f.rst

    .. sip:method:: PyQt5.QtGui.QScreen.serialNumber
        :returns:
            str
        :description: QtGui/QScreen-serialNumber-f.rst

    .. sip:method:: PyQt5.QtGui.QScreen.setOrientationUpdateMask
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.Qt.ScreenOrientations`, :sip:ref:`~PyQt5.QtCore.Qt.ScreenOrientation`]
        :description: QtGui/QScreen-setOrientationUpdateMask-f.rst

    .. sip:method:: PyQt5.QtGui.QScreen.size
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtGui/QScreen-size-f.rst

    .. sip:method:: PyQt5.QtGui.QScreen.transformBetween
        :args:
            :sip:ref:`~PyQt5.QtCore.Qt.ScreenOrientation`
            :sip:ref:`~PyQt5.QtCore.Qt.ScreenOrientation`
            :sip:ref:`~PyQt5.QtCore.QRect`
        :returns:
            :sip:ref:`~PyQt5.QtGui.QTransform`
        :description: QtGui/QScreen-transformBetween-f.rst

    .. sip:method:: PyQt5.QtGui.QScreen.virtualGeometry
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRect`
        :description: QtGui/QScreen-virtualGeometry-f.rst

    .. sip:method:: PyQt5.QtGui.QScreen.virtualSiblingAt
        :args:
            :sip:ref:`~PyQt5.QtCore.QPoint`
        :returns:
            :sip:ref:`~PyQt5.QtGui.QScreen`
        :description: QtGui/QScreen-virtualSiblingAt-f.rst

    .. sip:method:: PyQt5.QtGui.QScreen.virtualSiblings
        :returns:
            List[:sip:ref:`~PyQt5.QtGui.QScreen`]
        :description: QtGui/QScreen-virtualSiblings-f.rst

    .. sip:method:: PyQt5.QtGui.QScreen.virtualSize
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtGui/QScreen-virtualSize-f.rst

    .. sip:signal:: PyQt5.QtGui.QScreen.availableGeometryChanged
        :args:
            :sip:ref:`~PyQt5.QtCore.QRect`
        :description: QtGui/QScreen-availableGeometryChanged-s.rst

    .. sip:signal:: PyQt5.QtGui.QScreen.geometryChanged
        :args:
            :sip:ref:`~PyQt5.QtCore.QRect`
        :description: QtGui/QScreen-geometryChanged-s.rst

    .. sip:signal:: PyQt5.QtGui.QScreen.logicalDotsPerInchChanged
        :args:
            float
        :description: QtGui/QScreen-logicalDotsPerInchChanged-s.rst

    .. sip:signal:: PyQt5.QtGui.QScreen.orientationChanged
        :args:
            :sip:ref:`~PyQt5.QtCore.Qt.ScreenOrientation`
        :description: QtGui/QScreen-orientationChanged-s.rst

    .. sip:signal:: PyQt5.QtGui.QScreen.physicalDotsPerInchChanged
        :args:
            float
        :description: QtGui/QScreen-physicalDotsPerInchChanged-s.rst

    .. sip:signal:: PyQt5.QtGui.QScreen.physicalSizeChanged
        :args:
            :sip:ref:`~PyQt5.QtCore.QSizeF`
        :description: QtGui/QScreen-physicalSizeChanged-s.rst

    .. sip:signal:: PyQt5.QtGui.QScreen.primaryOrientationChanged
        :args:
            :sip:ref:`~PyQt5.QtCore.Qt.ScreenOrientation`
        :description: QtGui/QScreen-primaryOrientationChanged-s.rst

    .. sip:signal:: PyQt5.QtGui.QScreen.refreshRateChanged
        :args:
            float
        :description: QtGui/QScreen-refreshRateChanged-s.rst

    .. sip:signal:: PyQt5.QtGui.QScreen.virtualGeometryChanged
        :args:
            :sip:ref:`~PyQt5.QtCore.QRect`
        :description: QtGui/QScreen-virtualGeometryChanged-s.rst
