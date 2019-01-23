.. sip:method-description::
    :status: todo
    :pysig: 623c570a0ff0d5d7d29a7ced11b3367f
    :realsig: (QIODevice*)
    :digest: 5f7cc473adc84207a6b8def5a1fed8a8

Sets :sip:ref:`~PyQt5.QtGui.QImageReader`'s device to *device*. If a device has already been set, the old device is removed from :sip:ref:`~PyQt5.QtGui.QImageReader` and is otherwise left unchanged.

If the device is not already open, :sip:ref:`~PyQt5.QtGui.QImageReader` will attempt to open the device in :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag.ReadOnly` mode by calling open(). Note that this does not work for certain devices, such as QProcess, :sip:ref:`~PyQt5.QtNetwork.QTcpSocket` and :sip:ref:`~PyQt5.QtNetwork.QUdpSocket`, where more logic is required to open the device.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QImageReader.device`, :sip:ref:`~PyQt5.QtGui.QImageReader.setFileName`.
