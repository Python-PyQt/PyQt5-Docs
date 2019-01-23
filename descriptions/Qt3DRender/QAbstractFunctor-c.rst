.. sip:class-description::
    :status: todo
    :brief: Abstract base class for all functors
    :realname: Qt3DRender::QAbstractFunctor
    :digest: 798845e5180385032c41b442c8fdd9db

:sip:ref:`~PyQt5.Qt3DRender.QAbstractFunctor` is an abstract base class for all functors.

The :sip:ref:`~PyQt5.Qt3DRender.QAbstractFunctor` is used as a base class for all functors and data generators in :sip:ref:`~PyQt5.Qt3DRender` module.

When user defines a new functor or generator, they need to implement the QAbstractFunctor::id() method, which should be done using the ``QT3D_FUNCTOR`` macro in the class definition.
