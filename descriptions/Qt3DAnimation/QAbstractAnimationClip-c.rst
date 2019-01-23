.. sip:class-description::
    :status: todo
    :brief: The base class for types providing key frame animation data
    :realname: Qt3DAnimation::QAbstractAnimationClip
    :digest: f0b57e17ed934469df6e491beece0325

:sip:ref:`~PyQt5.Qt3DAnimation.QAbstractAnimationClip` is the base class for types providing key frame animation data.

To utilise the key frame animation framework in the Qt 3D Animation module the animator component in use needs to be provided with the key frame animation data. The animation data is provided by one of the concrete subclasses of :sip:ref:`~PyQt5.Qt3DAnimation.QAbstractAnimationClip`:

* :sip:ref:`~PyQt5.Qt3DAnimation.QAnimationClip`

* :sip:ref:`~PyQt5.Qt3DAnimation.QAnimationClipLoader`

QAnimationClip should be used when you want to create the animation data programmatically within your application. The actual data is set with a QAnimationClipData value type.

If you are loading baked animation data from a file, e.g. as created by an artist, then use the QAnimationClipLoader class and set its ``source`` property.

Once the animation clip has been populated with data using the above methods, the read-only duration property will be updated by the Qt 3D Animation backend.

The typical usage of animation clips is:

::

    auto animator = new QClipAnimator();
    auto clip = new QAnimationClipLoader();
    clip->setSource(QUrl::fromLocalFile("bounce.json"));
    animator->setClip(clip);
    animator->setChannelMapper(...);
    animator->setRunning(true);

Animation clips are also used as the leaf node values in animation blend trees:

::

    // Create leaf nodes of blend tree
    auto slideClipValue = new QClipBlendValue(
        new QAnimationClipLoader(QUrl::fromLocalFile("slide.json")));
    auto bounceClipValue = new QClipBlendValue(
        new QAnimationClipLoader(QUrl::fromLocalFile("bounce.json")));

    // Create blend tree inner node
    auto additiveNode = new QAdditiveClipBlend();
    additiveNode->setBaseClip(slideClipValue);
    additiveNode->setAdditiveClip(bounceClipValue);
    additiveNode->setAdditiveFactor(0.5f);

    // Run the animator
    auto animator = new QBlendedClipAnimator();
    animator->setBlendTree(additiveNode);
    animator->setChannelMapper(...);
    animator->setRunning(true);

.. seealso:: QAnimationClip, QAnimationClipLoader.
