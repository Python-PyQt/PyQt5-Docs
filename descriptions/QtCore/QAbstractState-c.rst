.. sip:class-description::
    :status: todo
    :brief: The base class of states of a QStateMachine
    :digest: 06dcefe0553c821bbcc31bf12c685b60

The :sip:ref:`~PyQt5.QtCore.QAbstractState` class is the base class of states of a :sip:ref:`~PyQt5.QtCore.QStateMachine`.

The :sip:ref:`~PyQt5.QtCore.QAbstractState` class is the abstract base class of states that are part of a :sip:ref:`~PyQt5.QtCore.QStateMachine`. It defines the interface that all state objects have in common. :sip:ref:`~PyQt5.QtCore.QAbstractState` is part of `The State Machine Framework <https://doc.qt.io/qt-5/statemachine-api.html>`_.

The :sip:ref:`~PyQt5.QtCore.QAbstractState.entered` signal is emitted when the state has been entered. The :sip:ref:`~PyQt5.QtCore.QAbstractState.exited` signal is emitted when the state has been exited.

The :sip:ref:`~PyQt5.QtCore.QAbstractState.parentState` function returns the state's parent state. The :sip:ref:`~PyQt5.QtCore.QAbstractState.machine` function returns the state machine that the state is part of.

.. _qabstractstate-subclassing:

Subclassing
-----------

The :sip:ref:`~PyQt5.QtCore.QAbstractState.onEntry` function is called when the state is entered; reimplement this function to perform custom processing when the state is entered.

The :sip:ref:`~PyQt5.QtCore.QAbstractState.onExit` function is called when the state is exited; reimplement this function to perform custom processing when the state is exited.
