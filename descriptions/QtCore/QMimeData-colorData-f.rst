.. sip:method-description::
    :status: todo
    :pysig: ed36a1ef76a59ee3f15180e0441188ad
    :realsig: () const
    :digest: ec462e91dc9d6b801d3ae6823d8a7e07

Returns a color if the data stored in the object represents a color (MIME type ``application/x-color``); otherwise returns a null variant.

A :sip:ref:`~PyQt5.QtCore.QVariant` is used because :sip:ref:`~PyQt5.QtCore.QMimeData` belongs to the Qt Core module, whereas :sip:ref:`~PyQt5.QtGui.QColor` belongs to Qt GUI. To convert the :sip:ref:`~PyQt5.QtCore.QVariant` to a :sip:ref:`~PyQt5.QtGui.QColor`, simply use qvariant_cast(). For example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_kernel_qmimedata.py
    :lines: 116-119

.. seealso:: :sip:ref:`~PyQt5.QtCore.QMimeData.hasColor`, :sip:ref:`~PyQt5.QtCore.QMimeData.setColorData`, :sip:ref:`~PyQt5.QtCore.QMimeData.data`.
