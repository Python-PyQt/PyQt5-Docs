.. sip:class-description::
    :status: todo
    :brief: Parallel group of animations
    :digest: 67d8bb2efc5d3b0445d3ee5c1171a7ae

The :sip:ref:`~PyQt5.QtCore.QParallelAnimationGroup` class provides a parallel group of animations.

:sip:ref:`~PyQt5.QtCore.QParallelAnimationGroup`--a :sip:ref:`~PyQt5.QtCore.QAnimationGroup`--starts all its animations when it is :sip:ref:`~PyQt5.QtCore.QAbstractAnimation.start` itself, i.e., runs all animations in parallel. The animation group finishes when the longest lasting animation has finished.

You can treat :sip:ref:`~PyQt5.QtCore.QParallelAnimationGroup` as any other :sip:ref:`~PyQt5.QtCore.QAbstractAnimation`, e.g., pause, resume, or add it to other animation groups.

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_animation_qparallelanimationgroup.py
    :lines: 43-47

In this example, ``anim1`` and ``anim2`` are two :sip:ref:`~PyQt5.QtCore.QPropertyAnimation`\ s that have already been set up.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QAnimationGroup`, :sip:ref:`~PyQt5.QtCore.QPropertyAnimation`, `The Animation Framework <https://doc.qt.io/qt-5/animation-overview.html>`_.
