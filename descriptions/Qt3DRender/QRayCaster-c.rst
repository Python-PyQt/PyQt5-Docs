.. sip:class-description::
    :status: todo
    :brief: Qt3DRender::QRayCaster is used to perform ray casting tests in 3d world coordinates
    :realname: Qt3DRender::QRayCaster
    :digest: 714c3d9e778d02db3f77fadd5eef7081

:sip:ref:`~PyQt5.Qt3DRender.QRayCaster` is used to perform ray casting tests in 3d world coordinates.

The 3d ray is defined by its origin, direction and length. It will be affected by the transformations applied to the entity it belongs to.

Ray casting tests will be performed every frame as long as the component is enabled. The hits property will be updated with the list of intersections.

.. seealso:: QAbstractRayCaster, QScreenRayCaster.
