.. sip:class-description::
    :status: todo
    :brief: Qt3DExtras::QSkyboxEntity is a convenience Qt3DCore::QEntity subclass that can be used to insert a skybox in a 3D scene
    :realname: Qt3DExtras::QSkyboxEntity
    :digest: 540c4a906bab7478049488b705fa25e1

:sip:ref:`~PyQt5.Qt3DExtras.QSkyboxEntity` is a convenience :sip:ref:`~PyQt5.Qt3DCore.QEntity` subclass that can be used to insert a skybox in a 3D scene.

By specifying a base name and an extension, :sip:ref:`~PyQt5.Qt3DExtras.QSkyboxEntity` will take care of building a TextureCubeMap to be rendered at runtime. The images in the source directory should match the pattern: **base** name + \* "_posx|_posy|_posz|_negx|_negy|_negz" + extension

By default the extension defaults to .png.

Be sure to disable frustum culling in the FrameGraph through which the skybox rendering happens.

**Note:** Please note that you shouldn't try to render a skybox with an orthographic projection.
