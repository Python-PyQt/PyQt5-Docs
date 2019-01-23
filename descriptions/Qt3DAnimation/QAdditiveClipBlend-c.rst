.. sip:class-description::
    :status: todo
    :brief: Performs an additive blend of two animation clips based on an additive factor
    :realname: Qt3DAnimation::QAdditiveClipBlend
    :digest: d3c9ad735770f8ca1adff71dae1b9e3b

Performs an additive blend of two animation clips based on an additive factor.

:sip:ref:`~PyQt5.Qt3DAnimation.QAdditiveClipBlend` can be useful to create advanced animation effects based on individual animation clips. For example, if you:

* set the baseClip property to a normal walk cycle animation clip and

* set the additiveClip property to a shaking head difference clip,

then adjusting the additiveFactor property will control how much of the additiveClip gets added on to the baseClip. This has he effect that with an additiveFactor of zero, this blend node will yield the original walk cycle clip. With an additiveFactor of 1, it will yield the walk cycle including a shaking head animation.

The blending operation implemented by this class is:

::

    resultClip = baseClip + additiveFactor * additiveClip

There is nothing stopping you from using values for the additiveFacor property outside the 0 to 1 range, but please be aware that the input animation clips may not be authored in such a way for this to make sense.

.. seealso:: QBlendedClipAnimator.
