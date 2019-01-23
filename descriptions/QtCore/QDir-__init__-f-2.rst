.. sip:method-description::
    :status: todo
    :pysig: 3461ff0d4f9fc076b76623c15fef5ea5
    :realsig: (const QString&,const QString&,QDir::SortFlags,QDir::Filters)
    :digest: 9828a5093c471d146a053cd41354eade

Constructs a :sip:ref:`~PyQt5.QtCore.QDir` with path *path*, that filters its entries by name using *nameFilter* and by attributes using *filters*. It also sorts the names using *sort*.

The default *nameFilter* is an empty string, which excludes nothing; the default *filters* is :sip:ref:`~PyQt5.QtCore.QDir.Filter.AllEntries`, which also means exclude nothing. The default *sort* is :sip:ref:`~PyQt5.QtCore.QDir.SortFlag.Name` | :sip:ref:`~PyQt5.QtCore.QDir.SortFlag.IgnoreCase`, i.e. sort by name case-insensitively.

If *path* is an empty string, :sip:ref:`~PyQt5.QtCore.QDir` uses "." (the current directory). If *nameFilter* is an empty string, :sip:ref:`~PyQt5.QtCore.QDir` uses the name filter "\*" (all files).

Note that *path* need not exist.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QDir.exists`, :sip:ref:`~PyQt5.QtCore.QDir.setPath`, :sip:ref:`~PyQt5.QtCore.QDir.setNameFilters`, :sip:ref:`~PyQt5.QtCore.QDir.setFilter`, :sip:ref:`~PyQt5.QtCore.QDir.setSorting`.
