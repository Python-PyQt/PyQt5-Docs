.. sip:method-description::
    :status: todo
    :pysig: ac23e808b45e02a842851f437e43398f
    :realsig: (QAbstractState*)
    :digest: 9867f1f1fd4286ad94f4f4a6e435959a

Sets this history state's default state to be the given *state*. *state* must be a sibling of this history state.

Note that this function does not set *state* as the initial state of its parent.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QHistoryState.defaultState`.
