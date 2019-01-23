.. sip:method-description::
    :status: todo
    :pysig: 36796edcde5818b5c2a893c687145dc8
    :realsig: (const QStringList&,QDir::Filters,QDir::SortFlags) const
    :digest: 608202cafdf522eabc3fff2a92e0f945

Returns a list of :sip:ref:`~PyQt5.QtCore.QFileInfo` objects for all the files and directories in the directory, ordered according to the name and attribute filters previously set with :sip:ref:`~PyQt5.QtCore.QDir.setNameFilters` and :sip:ref:`~PyQt5.QtCore.QDir.setFilter`, and sorted according to the flags set with :sip:ref:`~PyQt5.QtCore.QDir.setSorting`.

The name filter, file attribute filter, and sorting specification can be overridden using the *nameFilters*, *filters*, and *sort* arguments.

Returns an empty list if the directory is unreadable, does not exist, or if nothing matches the specification.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QDir.entryList`, :sip:ref:`~PyQt5.QtCore.QDir.setNameFilters`, :sip:ref:`~PyQt5.QtCore.QDir.setSorting`, :sip:ref:`~PyQt5.QtCore.QDir.setFilter`, :sip:ref:`~PyQt5.QtCore.QDir.isReadable`, :sip:ref:`~PyQt5.QtCore.QDir.exists`.
