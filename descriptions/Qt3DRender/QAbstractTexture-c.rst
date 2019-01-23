.. sip:class-description::
    :status: todo
    :brief: A base class to be used to provide textures
    :realname: Qt3DRender::QAbstractTexture
    :digest: 7b93ab3d9db93609327e348484224208

A base class to be used to provide textures.

The :sip:ref:`~PyQt5.Qt3DRender.QAbstractTexture` class shouldn't be used directly but rather through one of its subclasses. Each subclass implements a given texture target (2D, 2DArray, 3D, CubeMap ...) Each subclass provides a set of functors for each layer, cube map face and mipmap level. In turn the backend uses those functor to properly fill a corresponding OpenGL texture with data.
