.. sip:method-description::
    :status: todo
    :pysig: 904ca30fdd0af82f22d123e6ece3ccec
    :realsig: ()
    :digest: ae99dace608af35890f0439aa55304c1

Returns the local machine ID as known to the D-Bus system. Each node or host that runs D-Bus has a unique identifier that can be used to distinguish it from other hosts if they are sharing resources like the filesystem.

Note that the local machine ID is not guaranteed to be persistent across boots of the system, so this identifier should not be stored in persistent storage (like the filesystem). It is guaranteed to remain constant only during the lifetime of this boot session.
