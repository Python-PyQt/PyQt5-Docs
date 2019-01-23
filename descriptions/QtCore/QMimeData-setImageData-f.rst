.. sip:method-description::
    :status: todo
    :pysig: ed36a1ef76a59ee3f15180e0441188ad
    :realsig: (const QVariant&)
    :digest: b6457c411ef8033c2ffb54dc0326897c

Sets the data in the object to the given *image*.

A :sip:ref:`~PyQt5.QtCore.QVariant` is used because :sip:ref:`~PyQt5.QtCore.QMimeData` belongs to the Qt Core module, whereas :sip:ref:`~PyQt5.QtGui.QImage` belongs to Qt GUI. The conversion from :sip:ref:`~PyQt5.QtGui.QImage` to :sip:ref:`~PyQt5.QtCore.QVariant` is implicit. For example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_kernel_qmimedata.py
    :lines: 111-111

.. seealso:: :sip:ref:`~PyQt5.QtCore.QMimeData.imageData`, :sip:ref:`~PyQt5.QtCore.QMimeData.hasImage`, :sip:ref:`~PyQt5.QtCore.QMimeData.setData`.
