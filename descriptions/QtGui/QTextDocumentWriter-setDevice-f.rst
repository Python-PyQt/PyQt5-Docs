.. sip:method-description::
    :status: todo
    :pysig: 623c570a0ff0d5d7d29a7ced11b3367f
    :realsig: (QIODevice*)
    :digest: ade8e2866fea59101eac81710c6f9ca5

Sets the writer's device to the *device* specified. If a device has already been set, the old device is removed but otherwise left unchanged.

If the device is not already open, :sip:ref:`~PyQt5.QtGui.QTextDocumentWriter` will attempt to open the device in :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag.WriteOnly` mode by calling open().

**Note:** This will not work for certain devices, such as QProcess, :sip:ref:`~PyQt5.QtNetwork.QTcpSocket` and :sip:ref:`~PyQt5.QtNetwork.QUdpSocket`, where some configuration is required before the device can be opened.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QTextDocumentWriter.device`, :sip:ref:`~PyQt5.QtGui.QTextDocumentWriter.setFileName`.
