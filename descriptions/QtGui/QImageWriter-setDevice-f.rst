.. sip:method-description::
    :status: todo
    :pysig: 623c570a0ff0d5d7d29a7ced11b3367f
    :realsig: (QIODevice*)
    :digest: 5d8f9d03afa22523c7192e749de2ed9c

Sets :sip:ref:`~PyQt5.QtGui.QImageWriter`'s device to *device*. If a device has already been set, the old device is removed from :sip:ref:`~PyQt5.QtGui.QImageWriter` and is otherwise left unchanged.

If the device is not already open, :sip:ref:`~PyQt5.QtGui.QImageWriter` will attempt to open the device in :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag.WriteOnly` mode by calling open(). Note that this does not work for certain devices, such as QProcess, :sip:ref:`~PyQt5.QtNetwork.QTcpSocket` and :sip:ref:`~PyQt5.QtNetwork.QUdpSocket`, where more logic is required to open the device.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QImageWriter.device`, :sip:ref:`~PyQt5.QtGui.QImageWriter.setFileName`.
