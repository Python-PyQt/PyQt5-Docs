:orphan:

.. sip:class:: PyQt5.QtDBus.QDBusServiceWatcher
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtDBus/QDBusServiceWatcher-c.rst

    .. sip:enum:: PyQt5.QtDBus.QDBusServiceWatcher.WatchModeFlag
        :description: QtDBus/QDBusServiceWatcher-WatchModeFlag-e.rst

        .. sip:enum-member:: PyQt5.QtDBus.QDBusServiceWatcher.WatchModeFlag.WatchForOwnerChange
            :description: QtDBus/QDBusServiceWatcher-WatchModeFlag-WatchForOwnerChange-v.rst

        .. sip:enum-member:: PyQt5.QtDBus.QDBusServiceWatcher.WatchModeFlag.WatchForRegistration
            :description: QtDBus/QDBusServiceWatcher-WatchModeFlag-WatchForRegistration-v.rst

        .. sip:enum-member:: PyQt5.QtDBus.QDBusServiceWatcher.WatchModeFlag.WatchForUnregistration
            :description: QtDBus/QDBusServiceWatcher-WatchModeFlag-WatchForUnregistration-v.rst

    .. sip:method:: PyQt5.QtDBus.QDBusServiceWatcher.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtDBus/QDBusServiceWatcher-__init__-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusServiceWatcher.__init__
        :args:
            str
            :sip:ref:`~PyQt5.QtDBus.QDBusConnection`
            watchMode: Union[:sip:ref:`~PyQt5.QtDBus.QDBusServiceWatcher.WatchMode`, :sip:ref:`~PyQt5.QtDBus.QDBusServiceWatcher.WatchModeFlag`] = :sip:ref:`~PyQt5.QtDBus.QDBusServiceWatcher.WatchModeFlag.WatchForOwnerChange`
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtDBus/QDBusServiceWatcher-__init__-f-1.rst

    .. sip:method:: PyQt5.QtDBus.QDBusServiceWatcher.addWatchedService
        :args:
            str
        :description: QtDBus/QDBusServiceWatcher-addWatchedService-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusServiceWatcher.connection
        :returns:
            :sip:ref:`~PyQt5.QtDBus.QDBusConnection`
        :description: QtDBus/QDBusServiceWatcher-connection-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusServiceWatcher.removeWatchedService
        :args:
            str
        :returns:
            bool
        :description: QtDBus/QDBusServiceWatcher-removeWatchedService-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusServiceWatcher.setConnection
        :args:
            :sip:ref:`~PyQt5.QtDBus.QDBusConnection`
        :description: QtDBus/QDBusServiceWatcher-setConnection-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusServiceWatcher.setWatchedServices
        :args:
            Iterable[str]
        :description: QtDBus/QDBusServiceWatcher-setWatchedServices-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusServiceWatcher.setWatchMode
        :args:
            Union[:sip:ref:`~PyQt5.QtDBus.QDBusServiceWatcher.WatchMode`, :sip:ref:`~PyQt5.QtDBus.QDBusServiceWatcher.WatchModeFlag`]
        :description: QtDBus/QDBusServiceWatcher-setWatchMode-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusServiceWatcher.watchedServices
        :returns:
            List[str]
        :description: QtDBus/QDBusServiceWatcher-watchedServices-f.rst

    .. sip:method:: PyQt5.QtDBus.QDBusServiceWatcher.watchMode
        :returns:
            :sip:ref:`~PyQt5.QtDBus.QDBusServiceWatcher.WatchMode`
        :description: QtDBus/QDBusServiceWatcher-watchMode-f.rst

    .. sip:signal:: PyQt5.QtDBus.QDBusServiceWatcher.serviceOwnerChanged
        :args:
            str
            str
            str
        :description: QtDBus/QDBusServiceWatcher-serviceOwnerChanged-s.rst

    .. sip:signal:: PyQt5.QtDBus.QDBusServiceWatcher.serviceRegistered
        :args:
            str
        :description: QtDBus/QDBusServiceWatcher-serviceRegistered-s.rst

    .. sip:signal:: PyQt5.QtDBus.QDBusServiceWatcher.serviceUnregistered
        :args:
            str
        :description: QtDBus/QDBusServiceWatcher-serviceUnregistered-s.rst
