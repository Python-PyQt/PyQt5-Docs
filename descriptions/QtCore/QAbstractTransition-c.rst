.. sip:class-description::
    :status: todo
    :brief: The base class of transitions between QAbstractState objects
    :digest: dfc2fefcb4999f436a44862d7912c3bb

The :sip:ref:`~PyQt5.QtCore.QAbstractTransition` class is the base class of transitions between :sip:ref:`~PyQt5.QtCore.QAbstractState` objects.

The :sip:ref:`~PyQt5.QtCore.QAbstractTransition` class is the abstract base class of transitions between states (\ :sip:ref:`~PyQt5.QtCore.QAbstractState` objects) of a :sip:ref:`~PyQt5.QtCore.QStateMachine`. :sip:ref:`~PyQt5.QtCore.QAbstractTransition` is part of `The State Machine Framework <https://doc.qt.io/qt-5/statemachine-api.html>`_.

The :sip:ref:`~PyQt5.QtCore.QAbstractTransition.sourceState` function returns the source of the transition. The :sip:ref:`~PyQt5.QtCore.QAbstractTransition.targetStates` function returns the targets of the transition. The :sip:ref:`~PyQt5.QtCore.QAbstractTransition.machine` function returns the state machine that the transition is part of.

The :sip:ref:`~PyQt5.QtCore.QAbstractTransition.triggered` signal is emitted when the transition has been triggered.

Transitions can cause animations to be played. Use the addAnimation() function to add an animation to the transition.

.. _qabstracttransition-subclassing:

Subclassing
-----------

The :sip:ref:`~PyQt5.QtCore.QAbstractTransition.eventTest` function is called by the state machine to determine whether an event should trigger the transition. In your reimplementation you typically check the event type and cast the event object to the proper type, and check that one or more properties of the event meet your criteria.

The :sip:ref:`~PyQt5.QtCore.QAbstractTransition.onTransition` function is called when the transition is triggered; reimplement this function to perform custom processing for the transition.
