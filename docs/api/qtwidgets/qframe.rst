:orphan:

.. sip:class:: PyQt5.QtWidgets.QFrame
    :inherits: :sip:ref:`~PyQt5.QtWidgets.QWidget`
    :description: QtWidgets/QFrame-c.rst

    .. sip:enum:: PyQt5.QtWidgets.QFrame.Shadow
        :description: QtWidgets/QFrame-Shadow-e.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFrame.Shadow.Plain
            :description: QtWidgets/QFrame-Shadow-Plain-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFrame.Shadow.Raised
            :description: QtWidgets/QFrame-Shadow-Raised-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFrame.Shadow.Sunken
            :description: QtWidgets/QFrame-Shadow-Sunken-v.rst

    .. sip:enum:: PyQt5.QtWidgets.QFrame.Shape
        :description: QtWidgets/QFrame-Shape-e.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFrame.Shape.Box
            :description: QtWidgets/QFrame-Shape-Box-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFrame.Shape.HLine
            :description: QtWidgets/QFrame-Shape-HLine-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFrame.Shape.NoFrame
            :description: QtWidgets/QFrame-Shape-NoFrame-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFrame.Shape.Panel
            :description: QtWidgets/QFrame-Shape-Panel-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFrame.Shape.StyledPanel
            :description: QtWidgets/QFrame-Shape-StyledPanel-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFrame.Shape.VLine
            :description: QtWidgets/QFrame-Shape-VLine-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFrame.Shape.WinPanel
            :description: QtWidgets/QFrame-Shape-WinPanel-v.rst

    .. sip:enum:: PyQt5.QtWidgets.QFrame.StyleMask
        :description: QtWidgets/QFrame-StyleMask-e.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFrame.StyleMask.Shadow_Mask
            :description: QtWidgets/QFrame-StyleMask-Shadow_Mask-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QFrame.StyleMask.Shape_Mask
            :description: QtWidgets/QFrame-StyleMask-Shape_Mask-v.rst

    .. sip:method:: PyQt5.QtWidgets.QFrame.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
            flags: Union[:sip:ref:`~PyQt5.QtCore.Qt.WindowFlags`, :sip:ref:`~PyQt5.QtCore.Qt.WindowType`] = Qt.WindowFlags()
        :description: QtWidgets/QFrame-__init__-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFrame.changeEvent
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :description: QtWidgets/QFrame-changeEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFrame.drawFrame
        :args:
            :sip:ref:`~PyQt5.QtGui.QPainter`
        :description: QtWidgets/QFrame-drawFrame-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFrame.event
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtWidgets/QFrame-event-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFrame.frameRect
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRect`
        :description: QtWidgets/QFrame-frameRect-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFrame.frameShadow
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QFrame.Shadow`
        :description: QtWidgets/QFrame-frameShadow-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFrame.frameShape
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QFrame.Shape`
        :description: QtWidgets/QFrame-frameShape-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFrame.frameStyle
        :returns:
            int
        :description: QtWidgets/QFrame-frameStyle-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFrame.frameWidth
        :returns:
            int
        :description: QtWidgets/QFrame-frameWidth-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFrame.initStyleOption
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QStyleOptionFrame`
        :description: QtWidgets/QFrame-initStyleOption-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFrame.lineWidth
        :returns:
            int
        :description: QtWidgets/QFrame-lineWidth-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFrame.midLineWidth
        :returns:
            int
        :description: QtWidgets/QFrame-midLineWidth-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFrame.paintEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QPaintEvent`
        :description: QtWidgets/QFrame-paintEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFrame.setFrameRect
        :args:
            :sip:ref:`~PyQt5.QtCore.QRect`
        :description: QtWidgets/QFrame-setFrameRect-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFrame.setFrameShadow
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QFrame.Shadow`
        :description: QtWidgets/QFrame-setFrameShadow-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFrame.setFrameShape
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QFrame.Shape`
        :description: QtWidgets/QFrame-setFrameShape-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFrame.setFrameStyle
        :args:
            int
        :description: QtWidgets/QFrame-setFrameStyle-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFrame.setLineWidth
        :args:
            int
        :description: QtWidgets/QFrame-setLineWidth-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFrame.setMidLineWidth
        :args:
            int
        :description: QtWidgets/QFrame-setMidLineWidth-f.rst

    .. sip:method:: PyQt5.QtWidgets.QFrame.sizeHint
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtWidgets/QFrame-sizeHint-f.rst
