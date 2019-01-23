.. sip:method-description::
    :status: todo
    :pysig: c7ae001672a91f87b780c008caecf830
    :realsig: () const
    :digest: 0f3be09072dd1780ab53e5665bc930d7

Returns the lock file error status.

If :sip:ref:`~PyQt5.QtCore.QLockFile.tryLock` returns ``false``, this function can be called to find out the reason why the locking failed.
