.. sip:method-description::
    :status: todo
    :pysig: c0562f954e4d4c6616575d326105b78a
    :realsig: (QThread*)
    :digest: 0f696b6e5c9089516a08e84df2774b07

Returns a pointer to the event dispatcher object for the specified *thread*. If *thread* is zero, the current thread is used. If no event dispatcher exists for the specified thread, this function returns 0.

**Note:** If Qt is built without thread support, the *thread* argument is ignored.
