.. sip:method-description::
    :status: todo
    :pysig: fa7153f7ed1cb6c0fcf2ffb2fac21748
    :realsig: () const
    :digest: 5103f68442618b2af6f82ccea3fa3a2f

Returns the physical orientation of the camera sensor.

The value is the orientation angle (clockwise, in steps of 90 degrees) of the camera sensor in relation to the display in its natural orientation.

You can show the camera image in the correct orientation by rotating it by this value in the anti-clockwise direction.

For example, suppose a mobile device which is naturally in portrait orientation. The back-facing camera is mounted in landscape. If the top side of the camera sensor is aligned with the right edge of the screen in natural orientation, the value should be 270. If the top side of a front-facing camera sensor is aligned with the right of the screen, the value should be 90.
