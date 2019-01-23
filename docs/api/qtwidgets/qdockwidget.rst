:orphan:

.. sip:class:: PyQt5.QtWidgets.QDockWidget
    :inherits: :sip:ref:`~PyQt5.QtWidgets.QWidget`
    :description: QtWidgets/QDockWidget-c.rst

    .. sip:enum:: PyQt5.QtWidgets.QDockWidget.DockWidgetFeature
        :description: QtWidgets/QDockWidget-DockWidgetFeature-e.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QDockWidget.DockWidgetFeature.AllDockWidgetFeatures
            :description: QtWidgets/QDockWidget-DockWidgetFeature-AllDockWidgetFeatures-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QDockWidget.DockWidgetFeature.DockWidgetClosable
            :description: QtWidgets/QDockWidget-DockWidgetFeature-DockWidgetClosable-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QDockWidget.DockWidgetFeature.DockWidgetFloatable
            :description: QtWidgets/QDockWidget-DockWidgetFeature-DockWidgetFloatable-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QDockWidget.DockWidgetFeature.DockWidgetMovable
            :description: QtWidgets/QDockWidget-DockWidgetFeature-DockWidgetMovable-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QDockWidget.DockWidgetFeature.DockWidgetVerticalTitleBar
            :description: QtWidgets/QDockWidget-DockWidgetFeature-DockWidgetVerticalTitleBar-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QDockWidget.DockWidgetFeature.NoDockWidgetFeatures
            :description: QtWidgets/QDockWidget-DockWidgetFeature-NoDockWidgetFeatures-v.rst

    .. sip:method:: PyQt5.QtWidgets.QDockWidget.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
            flags: Union[:sip:ref:`~PyQt5.QtCore.Qt.WindowFlags`, :sip:ref:`~PyQt5.QtCore.Qt.WindowType`] = Qt.WindowFlags()
        :description: QtWidgets/QDockWidget-__init__-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDockWidget.__init__
        :args:
            str
            parent: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
            flags: Union[:sip:ref:`~PyQt5.QtCore.Qt.WindowFlags`, :sip:ref:`~PyQt5.QtCore.Qt.WindowType`] = Qt.WindowFlags()
        :description: QtWidgets/QDockWidget-__init__-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QDockWidget.allowedAreas
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.DockWidgetAreas`
        :description: QtWidgets/QDockWidget-allowedAreas-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDockWidget.changeEvent
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :description: QtWidgets/QDockWidget-changeEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDockWidget.closeEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QCloseEvent`
        :description: QtWidgets/QDockWidget-closeEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDockWidget.event
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtWidgets/QDockWidget-event-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDockWidget.features
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QDockWidget.DockWidgetFeatures`
        :description: QtWidgets/QDockWidget-features-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDockWidget.initStyleOption
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QStyleOptionDockWidget`
        :description: QtWidgets/QDockWidget-initStyleOption-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDockWidget.isAreaAllowed
        :args:
            :sip:ref:`~PyQt5.QtCore.Qt.DockWidgetArea`
        :returns:
            bool
        :description: QtWidgets/QDockWidget-isAreaAllowed-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDockWidget.isFloating
        :returns:
            bool
        :description: QtWidgets/QDockWidget-isFloating-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDockWidget.paintEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QPaintEvent`
        :description: QtWidgets/QDockWidget-paintEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDockWidget.setAllowedAreas
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.Qt.DockWidgetAreas`, :sip:ref:`~PyQt5.QtCore.Qt.DockWidgetArea`]
        :description: QtWidgets/QDockWidget-setAllowedAreas-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDockWidget.setFeatures
        :args:
            Union[:sip:ref:`~PyQt5.QtWidgets.QDockWidget.DockWidgetFeatures`, :sip:ref:`~PyQt5.QtWidgets.QDockWidget.DockWidgetFeature`]
        :description: QtWidgets/QDockWidget-setFeatures-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDockWidget.setFloating
        :args:
            bool
        :description: QtWidgets/QDockWidget-setFloating-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDockWidget.setTitleBarWidget
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :description: QtWidgets/QDockWidget-setTitleBarWidget-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDockWidget.setWidget
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :description: QtWidgets/QDockWidget-setWidget-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDockWidget.titleBarWidget
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :description: QtWidgets/QDockWidget-titleBarWidget-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDockWidget.toggleViewAction
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAction`
        :description: QtWidgets/QDockWidget-toggleViewAction-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDockWidget.widget
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :description: QtWidgets/QDockWidget-widget-f.rst

    .. sip:signal:: PyQt5.QtWidgets.QDockWidget.allowedAreasChanged
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.Qt.DockWidgetAreas`, :sip:ref:`~PyQt5.QtCore.Qt.DockWidgetArea`]
        :description: QtWidgets/QDockWidget-allowedAreasChanged-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QDockWidget.dockLocationChanged
        :args:
            :sip:ref:`~PyQt5.QtCore.Qt.DockWidgetArea`
        :description: QtWidgets/QDockWidget-dockLocationChanged-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QDockWidget.featuresChanged
        :args:
            Union[:sip:ref:`~PyQt5.QtWidgets.QDockWidget.DockWidgetFeatures`, :sip:ref:`~PyQt5.QtWidgets.QDockWidget.DockWidgetFeature`]
        :description: QtWidgets/QDockWidget-featuresChanged-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QDockWidget.topLevelChanged
        :args:
            bool
        :description: QtWidgets/QDockWidget-topLevelChanged-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QDockWidget.visibilityChanged
        :args:
            bool
        :description: QtWidgets/QDockWidget-visibilityChanged-s.rst
