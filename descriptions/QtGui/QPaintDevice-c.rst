.. sip:class-description::
    :status: todo
    :brief: The base class of objects that can be painted on with QPainter
    :digest: bdcd59790df0a626dc8ff079a57a3a59

The :sip:ref:`~PyQt5.QtGui.QPaintDevice` class is the base class of objects that can be painted on with :sip:ref:`~PyQt5.QtGui.QPainter`.

A paint device is an abstraction of a two-dimensional space that can be drawn on using a :sip:ref:`~PyQt5.QtGui.QPainter`. Its default coordinate system has its origin located at the top-left position. X increases to the right and Y increases downwards. The unit is one pixel.

The drawing capabilities of :sip:ref:`~PyQt5.QtGui.QPaintDevice` are currently implemented by the :sip:ref:`~PyQt5.QtWidgets.QWidget`, :sip:ref:`~PyQt5.QtGui.QImage`, :sip:ref:`~PyQt5.QtGui.QPixmap`, QGLPixelBuffer, :sip:ref:`~PyQt5.QtGui.QPicture`, and QPrinter subclasses.

To implement support for a new backend, you must derive from :sip:ref:`~PyQt5.QtGui.QPaintDevice` and reimplement the virtual :sip:ref:`~PyQt5.QtGui.QPaintDevice.paintEngine` function to tell :sip:ref:`~PyQt5.QtGui.QPainter` which paint engine should be used to draw on this particular device. Note that you also must create a corresponding paint engine to be able to draw on the device, i.e derive from :sip:ref:`~PyQt5.QtGui.QPaintEngine` and reimplement its virtual functions.

**Warning:** Qt requires that a :sip:ref:`~PyQt5.QtGui.QGuiApplication` object exists before any paint devices can be created. Paint devices access window system resources, and these resources are not initialized before an application object is created.

The :sip:ref:`~PyQt5.QtGui.QPaintDevice` class provides several functions returning the various device metrics: The :sip:ref:`~PyQt5.QtGui.QPaintDevice.depth` function returns its bit depth (number of bit planes). The :sip:ref:`~PyQt5.QtGui.QPaintDevice.height` function returns its height in default coordinate system units (e.g. pixels for :sip:ref:`~PyQt5.QtGui.QPixmap` and :sip:ref:`~PyQt5.QtWidgets.QWidget`) while :sip:ref:`~PyQt5.QtGui.QPaintDevice.heightMM` returns the height of the device in millimeters. Similiarily, the :sip:ref:`~PyQt5.QtGui.QPaintDevice.width` and :sip:ref:`~PyQt5.QtGui.QPaintDevice.widthMM` functions return the width of the device in default coordinate system units and in millimeters, respectively. Alternatively, the protected :sip:ref:`~PyQt5.QtGui.QPaintDevice.metric` function can be used to retrieve the metric information by specifying the desired :sip:ref:`~PyQt5.QtGui.QPaintDevice.PaintDeviceMetric.PaintDeviceMetric` as argument.

The :sip:ref:`~PyQt5.QtGui.QPaintDevice.logicalDpiX` and :sip:ref:`~PyQt5.QtGui.QPaintDevice.logicalDpiY` functions return the horizontal and vertical resolution of the device in dots per inch. The :sip:ref:`~PyQt5.QtGui.QPaintDevice.physicalDpiX` and :sip:ref:`~PyQt5.QtGui.QPaintDevice.physicalDpiY` functions also return the resolution of the device in dots per inch, but note that if the logical and physical resolution differ, the corresponding :sip:ref:`~PyQt5.QtGui.QPaintEngine` must handle the mapping. Finally, the :sip:ref:`~PyQt5.QtGui.QPaintDevice.colorCount` function returns the number of different colors available for the paint device.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPaintEngine`, :sip:ref:`~PyQt5.QtGui.QPainter`, `Coordinate System <https://doc.qt.io/qt-5/coordsys.html>`_, `Paint System <https://doc.qt.io/qt-5/paintsystem.html>`_.
