:orphan:

.. sip:class:: PyQt5.QtCore.QAbstractState
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtCore/QAbstractState-c.rst

    .. sip:method:: PyQt5.QtCore.QAbstractState.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QState` = None
        :description: QtCore/QAbstractState-__init__-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractState.active
        :returns:
            bool
        :description: QtCore/QAbstractState-active-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractState.event
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtCore/QAbstractState-event-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractState.machine
        :returns:
            :sip:ref:`~PyQt5.QtCore.QStateMachine`
        :description: QtCore/QAbstractState-machine-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractState.onEntry
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :description: QtCore/QAbstractState-onEntry-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractState.onExit
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :description: QtCore/QAbstractState-onExit-f.rst

    .. sip:method:: PyQt5.QtCore.QAbstractState.parentState
        :returns:
            :sip:ref:`~PyQt5.QtCore.QState`
        :description: QtCore/QAbstractState-parentState-f.rst

    .. sip:signal:: PyQt5.QtCore.QAbstractState.activeChanged
        :args:
            bool
        :description: QtCore/QAbstractState-activeChanged-s.rst

    .. sip:signal:: PyQt5.QtCore.QAbstractState.entered
        :description: QtCore/QAbstractState-entered-s.rst

    .. sip:signal:: PyQt5.QtCore.QAbstractState.exited
        :description: QtCore/QAbstractState-exited-s.rst
