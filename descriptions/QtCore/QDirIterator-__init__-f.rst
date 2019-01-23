.. sip:method-description::
    :status: todo
    :pysig: caa81533087beb0d1c9f62654d64af0a
    :realsig: (const QDir&,QDirIterator::IteratorFlags)
    :digest: 0956bfcc99a52b007370e586c7885e9e

Constructs a :sip:ref:`~PyQt5.QtCore.QDirIterator` that can iterate over *dir*'s entrylist, using *dir*'s name filters and regular filters. You can pass options via *flags* to decide how the directory should be iterated.

By default, *flags* is :sip:ref:`~PyQt5.QtCore.QDirIterator.IteratorFlag.NoIteratorFlags`, which provides the same behavior as in :sip:ref:`~PyQt5.QtCore.QDir.entryList`.

The sorting in *dir* is ignored.

**Note:** To list symlinks that point to non existing files, :sip:ref:`~PyQt5.QtCore.QDir.Filter.System` must be passed to the flags.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QDirIterator.hasNext`, :sip:ref:`~PyQt5.QtCore.QDirIterator.next`, IteratorFlags.
