.. sip:class-description::
    :status: todo
    :brief: Holds information when a triangle is picked
    :realname: Qt3DRender::QPickTriangleEvent
    :digest: 3ade996931bf96d98c205fc7065ed00a

The :sip:ref:`~PyQt5.Qt3DRender.QPickTriangleEvent` class holds information when a triangle is picked.

When QPickingSettings::pickMode() is set to :sip:ref:`~PyQt5.Qt3DRender.QPickingSettings.PickMethod.TrianglePicking`, the signals on QObjectPicker will carry an instance of :sip:ref:`~PyQt5.Qt3DRender.QPickTriangleEvent`.

This contains the details of the triangle that was picked.

**Note:** In the case of indexed rendering, the point indices are relative to the array of coordinates, not the array of indices.

.. seealso:: QPickingSettings, QPickEvent, QObjectPicker, QAttribute.
