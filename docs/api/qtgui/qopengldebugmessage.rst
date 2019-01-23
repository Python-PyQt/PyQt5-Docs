:orphan:

.. sip:class:: PyQt5.QtGui.QOpenGLDebugMessage
    :description: QtGui/QOpenGLDebugMessage-c.rst

    .. sip:enum:: PyQt5.QtGui.QOpenGLDebugMessage.Severity
        :description: QtGui/QOpenGLDebugMessage-Severity-e.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLDebugMessage.Severity.AnySeverity
            :description: QtGui/QOpenGLDebugMessage-Severity-AnySeverity-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLDebugMessage.Severity.HighSeverity
            :description: QtGui/QOpenGLDebugMessage-Severity-HighSeverity-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLDebugMessage.Severity.InvalidSeverity
            :description: QtGui/QOpenGLDebugMessage-Severity-InvalidSeverity-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLDebugMessage.Severity.LowSeverity
            :description: QtGui/QOpenGLDebugMessage-Severity-LowSeverity-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLDebugMessage.Severity.MediumSeverity
            :description: QtGui/QOpenGLDebugMessage-Severity-MediumSeverity-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLDebugMessage.Severity.NotificationSeverity
            :description: QtGui/QOpenGLDebugMessage-Severity-NotificationSeverity-v.rst

    .. sip:enum:: PyQt5.QtGui.QOpenGLDebugMessage.Source
        :description: QtGui/QOpenGLDebugMessage-Source-e.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLDebugMessage.Source.AnySource
            :description: QtGui/QOpenGLDebugMessage-Source-AnySource-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLDebugMessage.Source.APISource
            :description: QtGui/QOpenGLDebugMessage-Source-APISource-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLDebugMessage.Source.ApplicationSource
            :description: QtGui/QOpenGLDebugMessage-Source-ApplicationSource-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLDebugMessage.Source.InvalidSource
            :description: QtGui/QOpenGLDebugMessage-Source-InvalidSource-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLDebugMessage.Source.OtherSource
            :description: QtGui/QOpenGLDebugMessage-Source-OtherSource-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLDebugMessage.Source.ShaderCompilerSource
            :description: QtGui/QOpenGLDebugMessage-Source-ShaderCompilerSource-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLDebugMessage.Source.ThirdPartySource
            :description: QtGui/QOpenGLDebugMessage-Source-ThirdPartySource-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLDebugMessage.Source.WindowSystemSource
            :description: QtGui/QOpenGLDebugMessage-Source-WindowSystemSource-v.rst

    .. sip:enum:: PyQt5.QtGui.QOpenGLDebugMessage.Type
        :description: QtGui/QOpenGLDebugMessage-Type-e.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLDebugMessage.Type.AnyType
            :description: QtGui/QOpenGLDebugMessage-Type-AnyType-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLDebugMessage.Type.DeprecatedBehaviorType
            :description: QtGui/QOpenGLDebugMessage-Type-DeprecatedBehaviorType-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLDebugMessage.Type.ErrorType
            :description: QtGui/QOpenGLDebugMessage-Type-ErrorType-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLDebugMessage.Type.GroupPopType
            :description: QtGui/QOpenGLDebugMessage-Type-GroupPopType-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLDebugMessage.Type.GroupPushType
            :description: QtGui/QOpenGLDebugMessage-Type-GroupPushType-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLDebugMessage.Type.InvalidType
            :description: QtGui/QOpenGLDebugMessage-Type-InvalidType-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLDebugMessage.Type.MarkerType
            :description: QtGui/QOpenGLDebugMessage-Type-MarkerType-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLDebugMessage.Type.OtherType
            :description: QtGui/QOpenGLDebugMessage-Type-OtherType-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLDebugMessage.Type.PerformanceType
            :description: QtGui/QOpenGLDebugMessage-Type-PerformanceType-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLDebugMessage.Type.PortabilityType
            :description: QtGui/QOpenGLDebugMessage-Type-PortabilityType-v.rst

        .. sip:enum-member:: PyQt5.QtGui.QOpenGLDebugMessage.Type.UndefinedBehaviorType
            :description: QtGui/QOpenGLDebugMessage-Type-UndefinedBehaviorType-v.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLDebugMessage.__init__
        :description: QtGui/QOpenGLDebugMessage-__init__-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLDebugMessage.__init__
        :args:
            :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage`
        :description: QtGui/QOpenGLDebugMessage-__init__-f-1.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLDebugMessage.createApplicationMessage
        :args:
            str
            id: int = 0
            severity: :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Severity` = :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Severity.NotificationSeverity`
            type: :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Type` = :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Type.OtherType`
        :returns:
            :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage`
        :static:
        :description: QtGui/QOpenGLDebugMessage-createApplicationMessage-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLDebugMessage.createThirdPartyMessage
        :args:
            str
            id: int = 0
            severity: :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Severity` = :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Severity.NotificationSeverity`
            type: :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Type` = :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Type.OtherType`
        :returns:
            :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage`
        :static:
        :description: QtGui/QOpenGLDebugMessage-createThirdPartyMessage-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLDebugMessage.__eq__
        :args:
            :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage`
        :returns:
            bool
        :description: QtGui/QOpenGLDebugMessage-__eq__-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLDebugMessage.id
        :returns:
            int
        :description: QtGui/QOpenGLDebugMessage-id-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLDebugMessage.message
        :returns:
            str
        :description: QtGui/QOpenGLDebugMessage-message-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLDebugMessage.__ne__
        :args:
            :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage`
        :returns:
            bool
        :description: QtGui/QOpenGLDebugMessage-__ne__-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLDebugMessage.severity
        :returns:
            :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Severity`
        :description: QtGui/QOpenGLDebugMessage-severity-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLDebugMessage.source
        :returns:
            :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Source`
        :description: QtGui/QOpenGLDebugMessage-source-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLDebugMessage.swap
        :args:
            :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage`
        :description: QtGui/QOpenGLDebugMessage-swap-f.rst

    .. sip:method:: PyQt5.QtGui.QOpenGLDebugMessage.type
        :returns:
            :sip:ref:`~PyQt5.QtGui.QOpenGLDebugMessage.Type`
        :description: QtGui/QOpenGLDebugMessage-type-f.rst
