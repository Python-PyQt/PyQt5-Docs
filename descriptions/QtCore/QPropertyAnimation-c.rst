.. sip:class-description::
    :status: todo
    :brief: Animates Qt properties
    :digest: 002cc7c2d2282573e3f2e34c53dd0287

The :sip:ref:`~PyQt5.QtCore.QPropertyAnimation` class animates Qt properties.

:sip:ref:`~PyQt5.QtCore.QPropertyAnimation` interpolates over `Qt properties <https://doc.qt.io/qt-5/properties.html>`_. As property values are stored in :sip:ref:`~PyQt5.QtCore.QVariant`\ s, the class inherits :sip:ref:`~PyQt5.QtCore.QVariantAnimation`, and supports animation of the same :sip:ref:`~PyQt5.QtCore.QMetaType.Type` as its super class.

A class declaring properties must be a :sip:ref:`~PyQt5.QtCore.QObject`. To make it possible to animate a property, it must provide a setter (so that :sip:ref:`~PyQt5.QtCore.QPropertyAnimation` can set the property's value). Note that this makes it possible to animate many of Qt's widgets. Let's look at an example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_animation_qpropertyanimation.py
    :lines: 44-49

The property name and the :sip:ref:`~PyQt5.QtCore.QObject` instance of which property should be animated are passed to the constructor. You can then specify the start and end value of the property. The procedure is equal for properties in classes you have implemented yourself--just check with :sip:ref:`~PyQt5.QtCore.QVariantAnimation` that your :sip:ref:`~PyQt5.QtCore.QVariant` type is supported.

The :sip:ref:`~PyQt5.QtCore.QVariantAnimation` class description explains how to set up the animation in detail. Note, however, that if a start value is not set, the property will start at the value it had when the :sip:ref:`~PyQt5.QtCore.QPropertyAnimation` instance was created.

:sip:ref:`~PyQt5.QtCore.QPropertyAnimation` works like a charm on its own. For complex animations that, for instance, contain several objects, :sip:ref:`~PyQt5.QtCore.QAnimationGroup` is provided. An animation group is an animation that can contain other animations, and that can manage when its animations are played. Look at :sip:ref:`~PyQt5.QtCore.QParallelAnimationGroup` for an example.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QVariantAnimation`, :sip:ref:`~PyQt5.QtCore.QAnimationGroup`, `The Animation Framework <https://doc.qt.io/qt-5/animation-overview.html>`_.
