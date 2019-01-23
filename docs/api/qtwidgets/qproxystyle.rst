:orphan:

.. sip:class:: PyQt5.QtWidgets.QProxyStyle
    :inherits: :sip:ref:`~PyQt5.QtWidgets.QCommonStyle`
    :description: QtWidgets/QProxyStyle-c.rst

    .. sip:method:: PyQt5.QtWidgets.QProxyStyle.__init__
        :args:
            style: :sip:ref:`~PyQt5.QtWidgets.QStyle` = None
        :description: QtWidgets/QProxyStyle-__init__-f.rst

    .. sip:method:: PyQt5.QtWidgets.QProxyStyle.__init__
        :args:
            str
        :description: QtWidgets/QProxyStyle-__init__-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QProxyStyle.baseStyle
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QStyle`
        :description: QtWidgets/QProxyStyle-baseStyle-f.rst

    .. sip:method:: PyQt5.QtWidgets.QProxyStyle.drawComplexControl
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QStyle.ComplexControl`
            :sip:ref:`~PyQt5.QtWidgets.QStyleOptionComplex`
            :sip:ref:`~PyQt5.QtGui.QPainter`
            widget: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
        :description: QtWidgets/QProxyStyle-drawComplexControl-f.rst

    .. sip:method:: PyQt5.QtWidgets.QProxyStyle.drawControl
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QStyle.ControlElement`
            :sip:ref:`~PyQt5.QtWidgets.QStyleOption`
            :sip:ref:`~PyQt5.QtGui.QPainter`
            widget: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
        :description: QtWidgets/QProxyStyle-drawControl-f.rst

    .. sip:method:: PyQt5.QtWidgets.QProxyStyle.drawItemPixmap
        :args:
            :sip:ref:`~PyQt5.QtGui.QPainter`
            :sip:ref:`~PyQt5.QtCore.QRect`
            int
            :sip:ref:`~PyQt5.QtGui.QPixmap`
        :description: QtWidgets/QProxyStyle-drawItemPixmap-f.rst

    .. sip:method:: PyQt5.QtWidgets.QProxyStyle.drawItemText
        :args:
            :sip:ref:`~PyQt5.QtGui.QPainter`
            :sip:ref:`~PyQt5.QtCore.QRect`
            int
            :sip:ref:`~PyQt5.QtGui.QPalette`
            bool
            str
            textRole: :sip:ref:`~PyQt5.QtGui.QPalette.ColorRole` = :sip:ref:`~PyQt5.QtGui.QPalette.ColorRole.NoRole`
        :description: QtWidgets/QProxyStyle-drawItemText-f.rst

    .. sip:method:: PyQt5.QtWidgets.QProxyStyle.drawPrimitive
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QStyle.PrimitiveElement`
            :sip:ref:`~PyQt5.QtWidgets.QStyleOption`
            :sip:ref:`~PyQt5.QtGui.QPainter`
            widget: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
        :description: QtWidgets/QProxyStyle-drawPrimitive-f.rst

    .. sip:method:: PyQt5.QtWidgets.QProxyStyle.event
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtWidgets/QProxyStyle-event-f.rst

    .. sip:method:: PyQt5.QtWidgets.QProxyStyle.generatedIconPixmap
        :args:
            :sip:ref:`~PyQt5.QtGui.QIcon.Mode`
            :sip:ref:`~PyQt5.QtGui.QPixmap`
            :sip:ref:`~PyQt5.QtWidgets.QStyleOption`
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPixmap`
        :description: QtWidgets/QProxyStyle-generatedIconPixmap-f.rst

    .. sip:method:: PyQt5.QtWidgets.QProxyStyle.hitTestComplexControl
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QStyle.ComplexControl`
            :sip:ref:`~PyQt5.QtWidgets.QStyleOptionComplex`
            :sip:ref:`~PyQt5.QtCore.QPoint`
            widget: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QStyle.SubControl`
        :description: QtWidgets/QProxyStyle-hitTestComplexControl-f.rst

    .. sip:method:: PyQt5.QtWidgets.QProxyStyle.itemPixmapRect
        :args:
            :sip:ref:`~PyQt5.QtCore.QRect`
            int
            :sip:ref:`~PyQt5.QtGui.QPixmap`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRect`
        :description: QtWidgets/QProxyStyle-itemPixmapRect-f.rst

    .. sip:method:: PyQt5.QtWidgets.QProxyStyle.itemTextRect
        :args:
            :sip:ref:`~PyQt5.QtGui.QFontMetrics`
            :sip:ref:`~PyQt5.QtCore.QRect`
            int
            bool
            str
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRect`
        :description: QtWidgets/QProxyStyle-itemTextRect-f.rst

    .. sip:method:: PyQt5.QtWidgets.QProxyStyle.layoutSpacing
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QSizePolicy.ControlType`
            :sip:ref:`~PyQt5.QtWidgets.QSizePolicy.ControlType`
            :sip:ref:`~PyQt5.QtCore.Qt.Orientation`
            option: :sip:ref:`~PyQt5.QtWidgets.QStyleOption` = None
            widget: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
        :returns:
            int
        :description: QtWidgets/QProxyStyle-layoutSpacing-f.rst

    .. sip:method:: PyQt5.QtWidgets.QProxyStyle.pixelMetric
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QStyle.PixelMetric`
            option: :sip:ref:`~PyQt5.QtWidgets.QStyleOption` = None
            widget: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
        :returns:
            int
        :description: QtWidgets/QProxyStyle-pixelMetric-f.rst

    .. sip:method:: PyQt5.QtWidgets.QProxyStyle.polish
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :description: QtWidgets/QProxyStyle-polish-f.rst

    .. sip:method:: PyQt5.QtWidgets.QProxyStyle.polish
        :args:
            :sip:ref:`~PyQt5.QtGui.QPalette`
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPalette`
        :description: QtWidgets/QProxyStyle-polish-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QProxyStyle.polish
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QApplication`
        :description: QtWidgets/QProxyStyle-polish-f-2.rst

    .. sip:method:: PyQt5.QtWidgets.QProxyStyle.setBaseStyle
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QStyle`
        :description: QtWidgets/QProxyStyle-setBaseStyle-f.rst

    .. sip:method:: PyQt5.QtWidgets.QProxyStyle.sizeFromContents
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QStyle.ContentsType`
            :sip:ref:`~PyQt5.QtWidgets.QStyleOption`
            :sip:ref:`~PyQt5.QtCore.QSize`
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtWidgets/QProxyStyle-sizeFromContents-f.rst

    .. sip:method:: PyQt5.QtWidgets.QProxyStyle.standardIcon
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QStyle.StandardPixmap`
            option: :sip:ref:`~PyQt5.QtWidgets.QStyleOption` = None
            widget: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
        :returns:
            :sip:ref:`~PyQt5.QtGui.QIcon`
        :description: QtWidgets/QProxyStyle-standardIcon-f.rst

    .. sip:method:: PyQt5.QtWidgets.QProxyStyle.standardPalette
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPalette`
        :description: QtWidgets/QProxyStyle-standardPalette-f.rst

    .. sip:method:: PyQt5.QtWidgets.QProxyStyle.standardPixmap
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QStyle.StandardPixmap`
            :sip:ref:`~PyQt5.QtWidgets.QStyleOption`
            widget: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPixmap`
        :description: QtWidgets/QProxyStyle-standardPixmap-f.rst

    .. sip:method:: PyQt5.QtWidgets.QProxyStyle.styleHint
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QStyle.StyleHint`
            option: :sip:ref:`~PyQt5.QtWidgets.QStyleOption` = None
            widget: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
            returnData: :sip:ref:`~PyQt5.QtWidgets.QStyleHintReturn` = None
        :returns:
            int
        :description: QtWidgets/QProxyStyle-styleHint-f.rst

    .. sip:method:: PyQt5.QtWidgets.QProxyStyle.subControlRect
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QStyle.ComplexControl`
            :sip:ref:`~PyQt5.QtWidgets.QStyleOptionComplex`
            :sip:ref:`~PyQt5.QtWidgets.QStyle.SubControl`
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRect`
        :description: QtWidgets/QProxyStyle-subControlRect-f.rst

    .. sip:method:: PyQt5.QtWidgets.QProxyStyle.subElementRect
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QStyle.SubElement`
            :sip:ref:`~PyQt5.QtWidgets.QStyleOption`
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRect`
        :description: QtWidgets/QProxyStyle-subElementRect-f.rst

    .. sip:method:: PyQt5.QtWidgets.QProxyStyle.unpolish
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :description: QtWidgets/QProxyStyle-unpolish-f.rst

    .. sip:method:: PyQt5.QtWidgets.QProxyStyle.unpolish
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QApplication`
        :description: QtWidgets/QProxyStyle-unpolish-f-1.rst
