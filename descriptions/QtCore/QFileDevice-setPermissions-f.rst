.. sip:method-description::
    :status: todo
    :pysig: 952611f3f1f4908df13a852ca331aab2
    :realsig: (QFileDevice::Permissions)
    :digest: 8fe051ecfc08d19545e0c940f0bb2b2f

Sets the permissions for the file to the *permissions* specified. Returns ``true`` if successful, or ``false`` if the permissions cannot be modified.

**Warning:** This function does not manipulate ACLs, which may limit its effectiveness.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QFileDevice.permissions`.
