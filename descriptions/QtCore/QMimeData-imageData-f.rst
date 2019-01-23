.. sip:method-description::
    :status: todo
    :pysig: ed36a1ef76a59ee3f15180e0441188ad
    :realsig: () const
    :digest: 11e0d73083381f204e8cdfd1af1123c9

Returns a :sip:ref:`~PyQt5.QtCore.QVariant` storing a :sip:ref:`~PyQt5.QtGui.QImage` if the object can return an image; otherwise returns a null variant.

A :sip:ref:`~PyQt5.QtCore.QVariant` is used because :sip:ref:`~PyQt5.QtCore.QMimeData` belongs to the Qt Core module, whereas :sip:ref:`~PyQt5.QtGui.QImage` belongs to Qt GUI. To convert the :sip:ref:`~PyQt5.QtCore.QVariant` to a :sip:ref:`~PyQt5.QtGui.QImage`, simply use qvariant_cast(). For example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_kernel_qmimedata.py
    :lines: 103-106

.. seealso:: :sip:ref:`~PyQt5.QtCore.QMimeData.setImageData`, :sip:ref:`~PyQt5.QtCore.QMimeData.hasImage`.
