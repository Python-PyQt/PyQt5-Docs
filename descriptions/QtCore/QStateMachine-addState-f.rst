.. sip:method-description::
    :status: todo
    :pysig: ac23e808b45e02a842851f437e43398f
    :realsig: (QAbstractState*)
    :digest: aa6130f9d001b9db865e456b59695f7d

Adds the given *state* to this state machine. The state becomes a top-level state.

If the state is already in a different machine, it will first be removed from its old machine, and then added to this machine.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QStateMachine.removeState`, setInitialState().
