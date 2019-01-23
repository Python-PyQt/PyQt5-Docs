.. sip:class-description::
    :status: todo
    :brief: Identifies a unique object, such as a tagged token or stylus, which is used with a pointing device
    :digest: d5e78ec0c2ca9cd5acdbb40f589fab06

:sip:ref:`~PyQt5.QtGui.QPointingDeviceUniqueId` identifies a unique object, such as a tagged token or stylus, which is used with a pointing device.

QPointingDeviceUniqueIds can be compared for equality, and can be used as keys in a QHash. You get access to the numerical ID via numericId(), if the device supports such IDs. For future extensions, though, you should not use that function, but compare objects of this type using the equality operator.

This class is a thin wrapper around an integer ID. You pass it into and out of functions by value.

This type actively prevents you from holding it in a QList, because doing so would be very inefficient. Use a QVector instead, which has the same API as QList, but more efficient storage.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QTouchEvent.TouchPoint`.
