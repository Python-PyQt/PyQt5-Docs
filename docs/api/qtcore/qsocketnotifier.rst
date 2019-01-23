:orphan:

.. sip:class:: PyQt5.QtCore.QSocketNotifier
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtCore/QSocketNotifier-c.rst

    .. sip:enum:: PyQt5.QtCore.QSocketNotifier.Type
        :description: QtCore/QSocketNotifier-Type-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QSocketNotifier.Type.Exception
            :description: QtCore/QSocketNotifier-Type-Exception-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QSocketNotifier.Type.Read
            :description: QtCore/QSocketNotifier-Type-Read-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QSocketNotifier.Type.Write
            :description: QtCore/QSocketNotifier-Type-Write-v.rst

    .. sip:method:: PyQt5.QtCore.QSocketNotifier.__init__
        :args:
            sip.voidptr
            :sip:ref:`~PyQt5.QtCore.QSocketNotifier.Type`
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtCore/QSocketNotifier-__init__-f.rst

    .. sip:method:: PyQt5.QtCore.QSocketNotifier.event
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtCore/QSocketNotifier-event-f.rst

    .. sip:method:: PyQt5.QtCore.QSocketNotifier.isEnabled
        :returns:
            bool
        :description: QtCore/QSocketNotifier-isEnabled-f.rst

    .. sip:method:: PyQt5.QtCore.QSocketNotifier.setEnabled
        :args:
            bool
        :description: QtCore/QSocketNotifier-setEnabled-f.rst

    .. sip:method:: PyQt5.QtCore.QSocketNotifier.socket
        :returns:
            sip.voidptr
        :description: QtCore/QSocketNotifier-socket-f.rst

    .. sip:method:: PyQt5.QtCore.QSocketNotifier.type
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSocketNotifier.Type`
        :description: QtCore/QSocketNotifier-type-f.rst

    .. sip:signal:: PyQt5.QtCore.QSocketNotifier.activated
        :args:
            int
        :description: QtCore/QSocketNotifier-activated-s.rst
