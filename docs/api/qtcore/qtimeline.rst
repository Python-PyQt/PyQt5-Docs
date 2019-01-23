:orphan:

.. sip:class:: PyQt5.QtCore.QTimeLine
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtCore/QTimeLine-c.rst

    .. sip:enum:: PyQt5.QtCore.QTimeLine.CurveShape
        :description: QtCore/QTimeLine-CurveShape-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QTimeLine.CurveShape.CosineCurve
            :description: QtCore/QTimeLine-CurveShape-CosineCurve-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QTimeLine.CurveShape.EaseInCurve
            :description: QtCore/QTimeLine-CurveShape-EaseInCurve-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QTimeLine.CurveShape.EaseInOutCurve
            :description: QtCore/QTimeLine-CurveShape-EaseInOutCurve-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QTimeLine.CurveShape.EaseOutCurve
            :description: QtCore/QTimeLine-CurveShape-EaseOutCurve-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QTimeLine.CurveShape.LinearCurve
            :description: QtCore/QTimeLine-CurveShape-LinearCurve-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QTimeLine.CurveShape.SineCurve
            :description: QtCore/QTimeLine-CurveShape-SineCurve-v.rst

    .. sip:enum:: PyQt5.QtCore.QTimeLine.Direction
        :description: QtCore/QTimeLine-Direction-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QTimeLine.Direction.Backward
            :description: QtCore/QTimeLine-Direction-Backward-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QTimeLine.Direction.Forward
            :description: QtCore/QTimeLine-Direction-Forward-v.rst

    .. sip:enum:: PyQt5.QtCore.QTimeLine.State
        :description: QtCore/QTimeLine-State-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QTimeLine.State.NotRunning
            :description: QtCore/QTimeLine-State-NotRunning-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QTimeLine.State.Paused
            :description: QtCore/QTimeLine-State-Paused-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QTimeLine.State.Running
            :description: QtCore/QTimeLine-State-Running-v.rst

    .. sip:method:: PyQt5.QtCore.QTimeLine.__init__
        :args:
            duration: int = 1000
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtCore/QTimeLine-__init__-f.rst

    .. sip:method:: PyQt5.QtCore.QTimeLine.currentFrame
        :returns:
            int
        :description: QtCore/QTimeLine-currentFrame-f.rst

    .. sip:method:: PyQt5.QtCore.QTimeLine.currentTime
        :returns:
            int
        :description: QtCore/QTimeLine-currentTime-f.rst

    .. sip:method:: PyQt5.QtCore.QTimeLine.currentValue
        :returns:
            float
        :description: QtCore/QTimeLine-currentValue-f.rst

    .. sip:method:: PyQt5.QtCore.QTimeLine.curveShape
        :returns:
            :sip:ref:`~PyQt5.QtCore.QTimeLine.CurveShape`
        :description: QtCore/QTimeLine-curveShape-f.rst

    .. sip:method:: PyQt5.QtCore.QTimeLine.direction
        :returns:
            :sip:ref:`~PyQt5.QtCore.QTimeLine.Direction`
        :description: QtCore/QTimeLine-direction-f.rst

    .. sip:method:: PyQt5.QtCore.QTimeLine.duration
        :returns:
            int
        :description: QtCore/QTimeLine-duration-f.rst

    .. sip:method:: PyQt5.QtCore.QTimeLine.easingCurve
        :returns:
            :sip:ref:`~PyQt5.QtCore.QEasingCurve`
        :description: QtCore/QTimeLine-easingCurve-f.rst

    .. sip:method:: PyQt5.QtCore.QTimeLine.endFrame
        :returns:
            int
        :description: QtCore/QTimeLine-endFrame-f.rst

    .. sip:method:: PyQt5.QtCore.QTimeLine.frameForTime
        :args:
            int
        :returns:
            int
        :description: QtCore/QTimeLine-frameForTime-f.rst

    .. sip:method:: PyQt5.QtCore.QTimeLine.loopCount
        :returns:
            int
        :description: QtCore/QTimeLine-loopCount-f.rst

    .. sip:method:: PyQt5.QtCore.QTimeLine.resume
        :description: QtCore/QTimeLine-resume-f.rst

    .. sip:method:: PyQt5.QtCore.QTimeLine.setCurrentTime
        :args:
            int
        :description: QtCore/QTimeLine-setCurrentTime-f.rst

    .. sip:method:: PyQt5.QtCore.QTimeLine.setCurveShape
        :args:
            :sip:ref:`~PyQt5.QtCore.QTimeLine.CurveShape`
        :description: QtCore/QTimeLine-setCurveShape-f.rst

    .. sip:method:: PyQt5.QtCore.QTimeLine.setDirection
        :args:
            :sip:ref:`~PyQt5.QtCore.QTimeLine.Direction`
        :description: QtCore/QTimeLine-setDirection-f.rst

    .. sip:method:: PyQt5.QtCore.QTimeLine.setDuration
        :args:
            int
        :description: QtCore/QTimeLine-setDuration-f.rst

    .. sip:method:: PyQt5.QtCore.QTimeLine.setEasingCurve
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QEasingCurve`, :sip:ref:`~PyQt5.QtCore.QEasingCurve.Type`]
        :description: QtCore/QTimeLine-setEasingCurve-f.rst

    .. sip:method:: PyQt5.QtCore.QTimeLine.setEndFrame
        :args:
            int
        :description: QtCore/QTimeLine-setEndFrame-f.rst

    .. sip:method:: PyQt5.QtCore.QTimeLine.setFrameRange
        :args:
            int
            int
        :description: QtCore/QTimeLine-setFrameRange-f.rst

    .. sip:method:: PyQt5.QtCore.QTimeLine.setLoopCount
        :args:
            int
        :description: QtCore/QTimeLine-setLoopCount-f.rst

    .. sip:method:: PyQt5.QtCore.QTimeLine.setPaused
        :args:
            bool
        :description: QtCore/QTimeLine-setPaused-f.rst

    .. sip:method:: PyQt5.QtCore.QTimeLine.setStartFrame
        :args:
            int
        :description: QtCore/QTimeLine-setStartFrame-f.rst

    .. sip:method:: PyQt5.QtCore.QTimeLine.setUpdateInterval
        :args:
            int
        :description: QtCore/QTimeLine-setUpdateInterval-f.rst

    .. sip:method:: PyQt5.QtCore.QTimeLine.start
        :description: QtCore/QTimeLine-start-f.rst

    .. sip:method:: PyQt5.QtCore.QTimeLine.startFrame
        :returns:
            int
        :description: QtCore/QTimeLine-startFrame-f.rst

    .. sip:method:: PyQt5.QtCore.QTimeLine.state
        :returns:
            :sip:ref:`~PyQt5.QtCore.QTimeLine.State`
        :description: QtCore/QTimeLine-state-f.rst

    .. sip:method:: PyQt5.QtCore.QTimeLine.stop
        :description: QtCore/QTimeLine-stop-f.rst

    .. sip:method:: PyQt5.QtCore.QTimeLine.timerEvent
        :args:
            :sip:ref:`~PyQt5.QtCore.QTimerEvent`
        :description: QtCore/QTimeLine-timerEvent-f.rst

    .. sip:method:: PyQt5.QtCore.QTimeLine.toggleDirection
        :description: QtCore/QTimeLine-toggleDirection-f.rst

    .. sip:method:: PyQt5.QtCore.QTimeLine.updateInterval
        :returns:
            int
        :description: QtCore/QTimeLine-updateInterval-f.rst

    .. sip:method:: PyQt5.QtCore.QTimeLine.valueForTime
        :args:
            int
        :returns:
            float
        :description: QtCore/QTimeLine-valueForTime-f.rst

    .. sip:signal:: PyQt5.QtCore.QTimeLine.finished
        :description: QtCore/QTimeLine-finished-s.rst

    .. sip:signal:: PyQt5.QtCore.QTimeLine.frameChanged
        :args:
            int
        :description: QtCore/QTimeLine-frameChanged-s.rst

    .. sip:signal:: PyQt5.QtCore.QTimeLine.stateChanged
        :args:
            :sip:ref:`~PyQt5.QtCore.QTimeLine.State`
        :description: QtCore/QTimeLine-stateChanged-s.rst

    .. sip:signal:: PyQt5.QtCore.QTimeLine.valueChanged
        :args:
            float
        :description: QtCore/QTimeLine-valueChanged-s.rst
