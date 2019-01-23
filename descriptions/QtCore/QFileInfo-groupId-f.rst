.. sip:method-description::
    :status: todo
    :pysig: fa7153f7ed1cb6c0fcf2ffb2fac21748
    :realsig: () const
    :digest: b75533f0e5b100529a24694f911f31c9

Returns the id of the group the file belongs to.

On Windows and on systems where files do not have groups this function always returns (uint) -2.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QFileInfo.group`, :sip:ref:`~PyQt5.QtCore.QFileInfo.owner`, :sip:ref:`~PyQt5.QtCore.QFileInfo.ownerId`.
