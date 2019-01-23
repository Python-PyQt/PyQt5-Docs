.. sip:method-description::
    :status: todo
    :pysig: 827ed86539d0def97515425920f5c106
    :realsig: () const
    :digest: 37c2043f6fec096795aa0dd645fa863b

Returns the maximal consistent set of states (including parallel and final states) that this state machine is currently in. If a state ``s`` is in the configuration, it is always the case that the parent of ``s`` is also in c. Note, however, that the machine itself is not an explicit member of the configuration.
