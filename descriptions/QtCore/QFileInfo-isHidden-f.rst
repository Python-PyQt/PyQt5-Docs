.. sip:method-description::
    :status: todo
    :pysig: c506ff134babdd6e68ab3e6350e95305
    :realsig: () const
    :digest: ae0e725b900cff0b29a077a14e635489

Returns ``true`` if this is a `hidden' file; otherwise returns ``false``.

**Note:** This function returns ``true`` for the special entries "." and ".." on Unix, even though :sip:ref:`~PyQt5.QtCore.QDir.entryList` threats them as shown.
