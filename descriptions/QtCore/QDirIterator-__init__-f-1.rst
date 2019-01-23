.. sip:method-description::
    :status: todo
    :pysig: f187b640987eebc9a395763d5ef6c688
    :realsig: (const QString&,QDirIterator::IteratorFlags)
    :digest: 912d22045f3dd847e22203a40434a166

Constructs a :sip:ref:`~PyQt5.QtCore.QDirIterator` that can iterate over *path*. You can pass options via *flags* to decide how the directory should be iterated.

By default, *flags* is :sip:ref:`~PyQt5.QtCore.QDirIterator.IteratorFlag.NoIteratorFlags`, which provides the same behavior as in :sip:ref:`~PyQt5.QtCore.QDir.entryList`.

**Note:** To list symlinks that point to non existing files, :sip:ref:`~PyQt5.QtCore.QDir.Filter.System` must be passed to the flags.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QDirIterator.hasNext`, :sip:ref:`~PyQt5.QtCore.QDirIterator.next`, IteratorFlags.
