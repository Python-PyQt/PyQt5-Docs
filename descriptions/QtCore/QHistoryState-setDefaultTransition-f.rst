.. sip:method-description::
    :status: todo
    :pysig: 33c20c9f03bf00a77d42f0fe2e3915db
    :realsig: (QAbstractTransition*)
    :digest: e17cc7e7bbe18c2af3ac0069f979f955

Sets this history state's default transition to be the given *transition*. This will set the source state of the *transition* to the history state.

Note that the eventTest method of the *transition* will never be called.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QHistoryState.defaultTransition`.
