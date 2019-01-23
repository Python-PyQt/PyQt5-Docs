.. sip:class-description::
    :status: todo
    :brief: Timeline for controlling animations
    :digest: 4e134b26c8f909d1a2e666d50d7d8e90

The :sip:ref:`~PyQt5.QtCore.QTimeLine` class provides a timeline for controlling animations.

It's most commonly used to animate a GUI control by calling a slot periodically. You can construct a timeline by passing its duration in milliseconds to :sip:ref:`~PyQt5.QtCore.QTimeLine`'s constructor. The timeline's duration describes for how long the animation will run. Then you set a suitable frame range by calling :sip:ref:`~PyQt5.QtCore.QTimeLine.setFrameRange`. Finally connect the :sip:ref:`~PyQt5.QtCore.QTimeLine.frameChanged` signal to a suitable slot in the widget you wish to animate (for example, setValue() in QProgressBar). When you proceed to calling :sip:ref:`~PyQt5.QtCore.QTimeLine.start`, :sip:ref:`~PyQt5.QtCore.QTimeLine` will enter Running state, and start emitting :sip:ref:`~PyQt5.QtCore.QTimeLine.frameChanged` at regular intervals, causing your widget's connected property's value to grow from the lower end to the upper and of your frame range, at a steady rate. You can specify the update interval by calling :sip:ref:`~PyQt5.QtCore.QTimeLine.setUpdateInterval`. When done, :sip:ref:`~PyQt5.QtCore.QTimeLine` enters :sip:ref:`~PyQt5.QtCore.QTimeLine.State.NotRunning` state, and emits :sip:ref:`~PyQt5.QtCore.QTimeLine.finished`.

Example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qtimeline.py
    :lines: 54-66

By default the timeline runs once, from the beginning and towards the end, upon which you must call :sip:ref:`~PyQt5.QtCore.QTimeLine.start` again to restart from the beginning. To make the timeline loop, you can call :sip:ref:`~PyQt5.QtCore.QTimeLine.setLoopCount`, passing the number of times the timeline should run before finishing. The direction can also be changed, causing the timeline to run backward, by calling :sip:ref:`~PyQt5.QtCore.QTimeLine.setDirection`. You can also pause and unpause the timeline while it's running by calling :sip:ref:`~PyQt5.QtCore.QTimeLine.setPaused`. For interactive control, the :sip:ref:`~PyQt5.QtCore.QTimeLine.setCurrentTime` function is provided, which sets the time position of the time line directly. Although most useful in :sip:ref:`~PyQt5.QtCore.QTimeLine.State.NotRunning` state, (e.g., connected to a :sip:ref:`~PyQt5.QtCore.QTimeLine.valueChanged` signal in a QSlider,) this function can be called at any time.

The frame interface is useful for standard widgets, but :sip:ref:`~PyQt5.QtCore.QTimeLine` can be used to control any type of animation. The heart of :sip:ref:`~PyQt5.QtCore.QTimeLine` lies in the :sip:ref:`~PyQt5.QtCore.QTimeLine.valueForTime` function, which generates a *value* between 0 and 1 for a given time. This value is typically used to describe the steps of an animation, where 0 is the first step of an animation, and 1 is the last step. When running, :sip:ref:`~PyQt5.QtCore.QTimeLine` generates values between 0 and 1 by calling :sip:ref:`~PyQt5.QtCore.QTimeLine.valueForTime` and emitting :sip:ref:`~PyQt5.QtCore.QTimeLine.valueChanged`. By default, :sip:ref:`~PyQt5.QtCore.QTimeLine.valueForTime` applies an interpolation algorithm to generate these value. You can choose from a set of predefined timeline algorithms by calling :sip:ref:`~PyQt5.QtCore.QTimeLine.setCurveShape`.

Note that by default, :sip:ref:`~PyQt5.QtCore.QTimeLine` uses the EaseInOut curve shape, which provides a value that grows slowly, then grows steadily, and finally grows slowly. For a custom timeline, you can reimplement :sip:ref:`~PyQt5.QtCore.QTimeLine.valueForTime`, in which case :sip:ref:`~PyQt5.QtCore.QTimeLine`'s :sip:ref:`~PyQt5.QtCore.QTimeLine.curveShape` property is ignored.

.. seealso:: QProgressBarQProgressDialog.
