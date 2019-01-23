.. sip:method-description::
    :status: todo
    :pysig: d41d8cd98f00b204e9800998ecf8427e
    :realsig: ()
    :digest: 5591fe4f45425be969222134f94d6bde

Optimize the usage of this matrix from its current elements.

Some operations such as :sip:ref:`~PyQt5.QtGui.QMatrix4x4.translate`, :sip:ref:`~PyQt5.QtGui.QMatrix4x4.scale`, and :sip:ref:`~PyQt5.QtGui.QMatrix4x4.rotate` can be performed more efficiently if the matrix being modified is already known to be the identity, a previous :sip:ref:`~PyQt5.QtGui.QMatrix4x4.translate`, a previous :sip:ref:`~PyQt5.QtGui.QMatrix4x4.scale`, etc.

Normally the :sip:ref:`~PyQt5.QtGui.QMatrix4x4` class keeps track of this special type internally as operations are performed. However, if the matrix is modified directly with {QLoggingCategory::operator()}{operator()()} or :sip:ref:`~PyQt5.QtGui.QMatrix4x4.data`, then :sip:ref:`~PyQt5.QtGui.QMatrix4x4` will lose track of the special type and will revert to the safest but least efficient operations thereafter.

By calling  after directly modifying the matrix, the programmer can force :sip:ref:`~PyQt5.QtGui.QMatrix4x4` to recover the special type if the elements appear to conform to one of the known optimized types.

.. seealso:: operator()(), :sip:ref:`~PyQt5.QtGui.QMatrix4x4.data`, :sip:ref:`~PyQt5.QtGui.QMatrix4x4.translate`.
