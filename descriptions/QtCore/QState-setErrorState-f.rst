.. sip:method-description::
    :status: todo
    :pysig: ac23e808b45e02a842851f437e43398f
    :realsig: (QAbstractState*)
    :digest: 2c9c09dfa17e5994bc1042aa9904663e

Sets this state's error state to be the given *state*. If the error state is not set, or if it is set to 0, the state will inherit its parent's error state recursively. If no error state is set for the state itself or any of its ancestors, an error will cause the machine to stop executing and an error will be printed to the console.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QState.errorState`.
