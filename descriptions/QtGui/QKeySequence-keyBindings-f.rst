.. sip:method-description::
    :status: todo
    :pysig: 8bce7699eb508a32c72bd9eca6adaec9
    :realsig: (QKeySequence::StandardKey)
    :digest: 44f32c1544fe77850105741c33c51413

Returns a list of key bindings for the given *key*. The result of calling this function will vary based on the target platform. The first element of the list indicates the primary shortcut for the given platform. If the result contains more than one result, these can be considered alternative shortcuts on the same platform for the given *key*.
