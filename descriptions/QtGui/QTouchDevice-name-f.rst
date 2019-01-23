.. sip:method-description::
    :status: todo
    :pysig: 341be97d9aff90c9978347f66f945b77
    :realsig: () const
    :digest: cb90004ebb9cedbafacc60f56e566934

Returns the touch device name.

This string may often be empty. It is however useful for systems that have more than one touch input device because there it can be used to differentiate between the devices (i.e. to tell from which device a :sip:ref:`~PyQt5.QtGui.QTouchEvent` originates from).

.. seealso:: :sip:ref:`~PyQt5.QtGui.QTouchDevice.setName`.
