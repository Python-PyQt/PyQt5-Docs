.. sip:method-description::
    :status: todo
    :pysig: 341be97d9aff90c9978347f66f945b77
    :realsig: () const
    :digest: 19cca1c66ba2eefe62663c57709d46d8

Returns the group of the file. On Windows, on systems where files do not have groups, or if an error occurs, an empty string is returned.

This function can be time consuming under Unix (in the order of milliseconds).

.. seealso:: :sip:ref:`~PyQt5.QtCore.QFileInfo.groupId`, :sip:ref:`~PyQt5.QtCore.QFileInfo.owner`, :sip:ref:`~PyQt5.QtCore.QFileInfo.ownerId`.
