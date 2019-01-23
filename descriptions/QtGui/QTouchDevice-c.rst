.. sip:class-description::
    :status: todo
    :brief: Describes the device from which touch events originate
    :digest: 38ddbdfeef67a3722ffef0e5f0443db8

The :sip:ref:`~PyQt5.QtGui.QTouchDevice` class describes the device from which touch events originate.

Each :sip:ref:`~PyQt5.QtGui.QTouchEvent` contains a :sip:ref:`~PyQt5.QtGui.QTouchDevice` pointer to allow accessing device-specific properties like type and capabilities. It is the responsibility of the platform or generic plug-ins to register the available touch devices via QWindowSystemInterface before generating any touch events. Applications do not need to instantiate this class, they should just access the global instances pointed to by QTouchEvent::device().
