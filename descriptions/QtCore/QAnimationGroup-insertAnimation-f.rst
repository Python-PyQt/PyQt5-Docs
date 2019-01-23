.. sip:method-description::
    :status: todo
    :pysig: 1ec3d874bd465db020a1bd0702b3c5a6
    :realsig: (int,QAbstractAnimation*)
    :digest: a464352cb73d410464a7332d3148e0fe

Inserts *animation* into this animation group at *index*. If *index* is 0 the animation is inserted at the beginning. If *index* is :sip:ref:`~PyQt5.QtCore.QAnimationGroup.animationCount`, the animation is inserted at the end.

**Note:** The group takes ownership of the animation.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QAnimationGroup.takeAnimation`, :sip:ref:`~PyQt5.QtCore.QAnimationGroup.addAnimation`, :sip:ref:`~PyQt5.QtCore.QAnimationGroup.indexOfAnimation`, :sip:ref:`~PyQt5.QtCore.QAnimationGroup.removeAnimation`.
