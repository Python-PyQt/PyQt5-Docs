.. sip:class-description::
    :status: todo
    :brief: Provides the facility to load an existing Scene
    :realname: Qt3DRender::QSceneLoader
    :digest: e72ab91db71d4d3e26357bd9950842a1

Provides the facility to load an existing Scene.

Given a 3D source file, the :sip:ref:`~PyQt5.Qt3DRender.QSceneLoader` will try to parse it and build a tree of :sip:ref:`~PyQt5.Qt3DCore.QEntity` objects with proper :sip:ref:`~PyQt5.Qt3DRender.QGeometryRenderer`, :sip:ref:`~PyQt5.Qt3DCore.QTransform` and :sip:ref:`~PyQt5.Qt3DRender.QMaterial` components.

The loader will try to determine the best material to be used based on the properties of the model file. If you wish to use a custom material, you will have to traverse the tree and replace the default associated materials with yours.

As the name implies, :sip:ref:`~PyQt5.Qt3DRender.QSceneLoader` loads a complete scene subtree. If you wish to load a single piece of geometry, you should rather use the :sip:ref:`~PyQt5.Qt3DRender.QMesh` instead.

:sip:ref:`~PyQt5.Qt3DRender.QSceneLoader` internally relies on the use of plugins to support a wide variety of 3D file formats. Here is a list of formats that are supported by Qt3D.

**Note:** this component shouldn't be shared among several :sip:ref:`~PyQt5.Qt3DCore.QEntity` instances. Undefined behavior will result.

.. seealso:: :sip:ref:`~PyQt5.Qt3DRender.QMesh`, :sip:ref:`~PyQt5.Qt3DRender.QGeometryRenderer`.
