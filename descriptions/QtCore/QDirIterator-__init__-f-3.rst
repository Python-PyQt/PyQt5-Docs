.. sip:method-description::
    :status: todo
    :pysig: b0065898dfca5e516211cf9afa6784af
    :realsig: (const QString&,const QStringList&,QDir::Filters,QDirIterator::IteratorFlags)
    :digest: a9a21b7a2de1d3f83f0b4558abf4e795

Constructs a :sip:ref:`~PyQt5.QtCore.QDirIterator` that can iterate over *path*, using *nameFilters* and *filters*. You can pass options via *flags* to decide how the directory should be iterated.

By default, *flags* is :sip:ref:`~PyQt5.QtCore.QDirIterator.IteratorFlag.NoIteratorFlags`, which provides the same behavior as :sip:ref:`~PyQt5.QtCore.QDir.entryList`.

**Note:** To list symlinks that point to non existing files, :sip:ref:`~PyQt5.QtCore.QDir.Filter.System` must be passed to the flags.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QDirIterator.hasNext`, :sip:ref:`~PyQt5.QtCore.QDirIterator.next`, IteratorFlags.
