:orphan:

.. sip:class:: PyQt5.QtWidgets.QGraphicsView
    :inherits: :sip:ref:`~PyQt5.QtWidgets.QAbstractScrollArea`
    :description: QtWidgets/QGraphicsView-c.rst

    .. sip:enum:: PyQt5.QtWidgets.QGraphicsView.CacheModeFlag
        :description: QtWidgets/QGraphicsView-CacheModeFlag-e.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QGraphicsView.CacheModeFlag.CacheBackground
            :description: QtWidgets/QGraphicsView-CacheModeFlag-CacheBackground-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QGraphicsView.CacheModeFlag.CacheNone
            :description: QtWidgets/QGraphicsView-CacheModeFlag-CacheNone-v.rst

    .. sip:enum:: PyQt5.QtWidgets.QGraphicsView.DragMode
        :description: QtWidgets/QGraphicsView-DragMode-e.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QGraphicsView.DragMode.NoDrag
            :description: QtWidgets/QGraphicsView-DragMode-NoDrag-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QGraphicsView.DragMode.RubberBandDrag
            :description: QtWidgets/QGraphicsView-DragMode-RubberBandDrag-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QGraphicsView.DragMode.ScrollHandDrag
            :description: QtWidgets/QGraphicsView-DragMode-ScrollHandDrag-v.rst

    .. sip:enum:: PyQt5.QtWidgets.QGraphicsView.OptimizationFlag
        :description: QtWidgets/QGraphicsView-OptimizationFlag-e.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QGraphicsView.OptimizationFlag.DontAdjustForAntialiasing
            :description: QtWidgets/QGraphicsView-OptimizationFlag-DontAdjustForAntialiasing-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QGraphicsView.OptimizationFlag.DontClipPainter
            :description: QtWidgets/QGraphicsView-OptimizationFlag-DontClipPainter-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QGraphicsView.OptimizationFlag.DontSavePainterState
            :description: QtWidgets/QGraphicsView-OptimizationFlag-DontSavePainterState-v.rst

    .. sip:enum:: PyQt5.QtWidgets.QGraphicsView.ViewportAnchor
        :description: QtWidgets/QGraphicsView-ViewportAnchor-e.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QGraphicsView.ViewportAnchor.AnchorUnderMouse
            :description: QtWidgets/QGraphicsView-ViewportAnchor-AnchorUnderMouse-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QGraphicsView.ViewportAnchor.AnchorViewCenter
            :description: QtWidgets/QGraphicsView-ViewportAnchor-AnchorViewCenter-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QGraphicsView.ViewportAnchor.NoAnchor
            :description: QtWidgets/QGraphicsView-ViewportAnchor-NoAnchor-v.rst

    .. sip:enum:: PyQt5.QtWidgets.QGraphicsView.ViewportUpdateMode
        :description: QtWidgets/QGraphicsView-ViewportUpdateMode-e.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QGraphicsView.ViewportUpdateMode.BoundingRectViewportUpdate
            :description: QtWidgets/QGraphicsView-ViewportUpdateMode-BoundingRectViewportUpdate-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QGraphicsView.ViewportUpdateMode.FullViewportUpdate
            :description: QtWidgets/QGraphicsView-ViewportUpdateMode-FullViewportUpdate-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QGraphicsView.ViewportUpdateMode.MinimalViewportUpdate
            :description: QtWidgets/QGraphicsView-ViewportUpdateMode-MinimalViewportUpdate-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QGraphicsView.ViewportUpdateMode.NoViewportUpdate
            :description: QtWidgets/QGraphicsView-ViewportUpdateMode-NoViewportUpdate-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QGraphicsView.ViewportUpdateMode.SmartViewportUpdate
            :description: QtWidgets/QGraphicsView-ViewportUpdateMode-SmartViewportUpdate-v.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
        :description: QtWidgets/QGraphicsView-__init__-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.__init__
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QGraphicsScene`
            parent: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
        :description: QtWidgets/QGraphicsView-__init__-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.alignment
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.Alignment`
        :description: QtWidgets/QGraphicsView-alignment-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.backgroundBrush
        :returns:
            :sip:ref:`~PyQt5.QtGui.QBrush`
        :description: QtWidgets/QGraphicsView-backgroundBrush-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.cacheMode
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QGraphicsView.CacheMode`
        :description: QtWidgets/QGraphicsView-cacheMode-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.centerOn
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QPointF`, :sip:ref:`~PyQt5.QtCore.QPoint`]
        :description: QtWidgets/QGraphicsView-centerOn-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.centerOn
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QGraphicsItem`
        :description: QtWidgets/QGraphicsView-centerOn-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.centerOn
        :args:
            float
            float
        :description: QtWidgets/QGraphicsView-centerOn-f-2.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.contextMenuEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QContextMenuEvent`
        :description: QtWidgets/QGraphicsView-contextMenuEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.dragEnterEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QDragEnterEvent`
        :description: QtWidgets/QGraphicsView-dragEnterEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.dragLeaveEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QDragLeaveEvent`
        :description: QtWidgets/QGraphicsView-dragLeaveEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.dragMode
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QGraphicsView.DragMode`
        :description: QtWidgets/QGraphicsView-dragMode-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.dragMoveEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QDragMoveEvent`
        :description: QtWidgets/QGraphicsView-dragMoveEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.drawBackground
        :args:
            :sip:ref:`~PyQt5.QtGui.QPainter`
            :sip:ref:`~PyQt5.QtCore.QRectF`
        :description: QtWidgets/QGraphicsView-drawBackground-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.drawForeground
        :args:
            :sip:ref:`~PyQt5.QtGui.QPainter`
            :sip:ref:`~PyQt5.QtCore.QRectF`
        :description: QtWidgets/QGraphicsView-drawForeground-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.dropEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QDropEvent`
        :description: QtWidgets/QGraphicsView-dropEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.ensureVisible
        :args:
            :sip:ref:`~PyQt5.QtCore.QRectF`
            xMargin: int = 50
            yMargin: int = 50
        :description: QtWidgets/QGraphicsView-ensureVisible-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.ensureVisible
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QGraphicsItem`
            xMargin: int = 50
            yMargin: int = 50
        :description: QtWidgets/QGraphicsView-ensureVisible-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.ensureVisible
        :args:
            float
            float
            float
            float
            xMargin: int = 50
            yMargin: int = 50
        :description: QtWidgets/QGraphicsView-ensureVisible-f-2.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.event
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtWidgets/QGraphicsView-event-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.fitInView
        :args:
            :sip:ref:`~PyQt5.QtCore.QRectF`
            mode: :sip:ref:`~PyQt5.QtCore.Qt.AspectRatioMode` = :sip:ref:`~PyQt5.QtCore.Qt.AspectRatioMode.IgnoreAspectRatio`
        :description: QtWidgets/QGraphicsView-fitInView-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.fitInView
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QGraphicsItem`
            mode: :sip:ref:`~PyQt5.QtCore.Qt.AspectRatioMode` = :sip:ref:`~PyQt5.QtCore.Qt.AspectRatioMode.IgnoreAspectRatio`
        :description: QtWidgets/QGraphicsView-fitInView-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.fitInView
        :args:
            float
            float
            float
            float
            mode: :sip:ref:`~PyQt5.QtCore.Qt.AspectRatioMode` = :sip:ref:`~PyQt5.QtCore.Qt.AspectRatioMode.IgnoreAspectRatio`
        :description: QtWidgets/QGraphicsView-fitInView-f-2.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.focusInEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QFocusEvent`
        :description: QtWidgets/QGraphicsView-focusInEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.focusNextPrevChild
        :args:
            bool
        :returns:
            bool
        :description: QtWidgets/QGraphicsView-focusNextPrevChild-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.focusOutEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QFocusEvent`
        :description: QtWidgets/QGraphicsView-focusOutEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.foregroundBrush
        :returns:
            :sip:ref:`~PyQt5.QtGui.QBrush`
        :description: QtWidgets/QGraphicsView-foregroundBrush-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.inputMethodEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QInputMethodEvent`
        :description: QtWidgets/QGraphicsView-inputMethodEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.inputMethodQuery
        :args:
            :sip:ref:`~PyQt5.QtCore.Qt.InputMethodQuery`
        :returns:
            Any
        :description: QtWidgets/QGraphicsView-inputMethodQuery-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.invalidateScene
        :args:
            rect: :sip:ref:`~PyQt5.QtCore.QRectF` = QRectF()
            layers: Union[:sip:ref:`~PyQt5.QtWidgets.QGraphicsScene.SceneLayers`, :sip:ref:`~PyQt5.QtWidgets.QGraphicsScene.SceneLayer`] = :sip:ref:`~PyQt5.QtWidgets.QGraphicsScene.SceneLayer.AllLayers`
        :description: QtWidgets/QGraphicsView-invalidateScene-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.isInteractive
        :returns:
            bool
        :description: QtWidgets/QGraphicsView-isInteractive-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.isTransformed
        :returns:
            bool
        :description: QtWidgets/QGraphicsView-isTransformed-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.itemAt
        :args:
            :sip:ref:`~PyQt5.QtCore.QPoint`
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QGraphicsItem`
        :description: QtWidgets/QGraphicsView-itemAt-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.itemAt
        :args:
            int
            int
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QGraphicsItem`
        :description: QtWidgets/QGraphicsView-itemAt-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.items
        :returns:
            List[:sip:ref:`~PyQt5.QtWidgets.QGraphicsItem`]
        :description: QtWidgets/QGraphicsView-items-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.items
        :args:
            :sip:ref:`~PyQt5.QtCore.QPoint`
        :returns:
            List[:sip:ref:`~PyQt5.QtWidgets.QGraphicsItem`]
        :description: QtWidgets/QGraphicsView-items-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.items
        :args:
            int
            int
        :returns:
            List[:sip:ref:`~PyQt5.QtWidgets.QGraphicsItem`]
        :description: QtWidgets/QGraphicsView-items-f-2.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.items
        :args:
            :sip:ref:`~PyQt5.QtCore.QRect`
            mode: :sip:ref:`~PyQt5.QtCore.Qt.ItemSelectionMode` = :sip:ref:`~PyQt5.QtCore.Qt.ItemSelectionMode.IntersectsItemShape`
        :returns:
            List[:sip:ref:`~PyQt5.QtWidgets.QGraphicsItem`]
        :description: QtWidgets/QGraphicsView-items-f-3.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.items
        :args:
            :sip:ref:`~PyQt5.QtGui.QPolygon`
            mode: :sip:ref:`~PyQt5.QtCore.Qt.ItemSelectionMode` = :sip:ref:`~PyQt5.QtCore.Qt.ItemSelectionMode.IntersectsItemShape`
        :returns:
            List[:sip:ref:`~PyQt5.QtWidgets.QGraphicsItem`]
        :description: QtWidgets/QGraphicsView-items-f-4.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.items
        :args:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
            mode: :sip:ref:`~PyQt5.QtCore.Qt.ItemSelectionMode` = :sip:ref:`~PyQt5.QtCore.Qt.ItemSelectionMode.IntersectsItemShape`
        :returns:
            List[:sip:ref:`~PyQt5.QtWidgets.QGraphicsItem`]
        :description: QtWidgets/QGraphicsView-items-f-5.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.items
        :args:
            int
            int
            int
            int
            mode: :sip:ref:`~PyQt5.QtCore.Qt.ItemSelectionMode` = :sip:ref:`~PyQt5.QtCore.Qt.ItemSelectionMode.IntersectsItemShape`
        :returns:
            List[:sip:ref:`~PyQt5.QtWidgets.QGraphicsItem`]
        :description: QtWidgets/QGraphicsView-items-f-6.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.keyPressEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QKeyEvent`
        :description: QtWidgets/QGraphicsView-keyPressEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.keyReleaseEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QKeyEvent`
        :description: QtWidgets/QGraphicsView-keyReleaseEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.mapFromScene
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QPointF`, :sip:ref:`~PyQt5.QtCore.QPoint`]
        :returns:
            :sip:ref:`~PyQt5.QtCore.QPoint`
        :description: QtWidgets/QGraphicsView-mapFromScene-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.mapFromScene
        :args:
            :sip:ref:`~PyQt5.QtCore.QRectF`
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPolygon`
        :description: QtWidgets/QGraphicsView-mapFromScene-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.mapFromScene
        :args:
            :sip:ref:`~PyQt5.QtGui.QPolygonF`
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPolygon`
        :description: QtWidgets/QGraphicsView-mapFromScene-f-2.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.mapFromScene
        :args:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :description: QtWidgets/QGraphicsView-mapFromScene-f-3.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.mapFromScene
        :args:
            float
            float
        :returns:
            :sip:ref:`~PyQt5.QtCore.QPoint`
        :description: QtWidgets/QGraphicsView-mapFromScene-f-4.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.mapFromScene
        :args:
            float
            float
            float
            float
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPolygon`
        :description: QtWidgets/QGraphicsView-mapFromScene-f-5.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.mapToScene
        :args:
            :sip:ref:`~PyQt5.QtCore.QPoint`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QPointF`
        :description: QtWidgets/QGraphicsView-mapToScene-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.mapToScene
        :args:
            :sip:ref:`~PyQt5.QtCore.QRect`
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPolygonF`
        :description: QtWidgets/QGraphicsView-mapToScene-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.mapToScene
        :args:
            :sip:ref:`~PyQt5.QtGui.QPolygon`
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPolygonF`
        :description: QtWidgets/QGraphicsView-mapToScene-f-2.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.mapToScene
        :args:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPainterPath`
        :description: QtWidgets/QGraphicsView-mapToScene-f-3.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.mapToScene
        :args:
            int
            int
        :returns:
            :sip:ref:`~PyQt5.QtCore.QPointF`
        :description: QtWidgets/QGraphicsView-mapToScene-f-4.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.mapToScene
        :args:
            int
            int
            int
            int
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPolygonF`
        :description: QtWidgets/QGraphicsView-mapToScene-f-5.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.mouseDoubleClickEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QMouseEvent`
        :description: QtWidgets/QGraphicsView-mouseDoubleClickEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.mouseMoveEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QMouseEvent`
        :description: QtWidgets/QGraphicsView-mouseMoveEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.mousePressEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QMouseEvent`
        :description: QtWidgets/QGraphicsView-mousePressEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.mouseReleaseEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QMouseEvent`
        :description: QtWidgets/QGraphicsView-mouseReleaseEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.optimizationFlags
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QGraphicsView.OptimizationFlags`
        :description: QtWidgets/QGraphicsView-optimizationFlags-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.paintEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QPaintEvent`
        :description: QtWidgets/QGraphicsView-paintEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.render
        :args:
            :sip:ref:`~PyQt5.QtGui.QPainter`
            target: :sip:ref:`~PyQt5.QtCore.QRectF` = QRectF()
            source: :sip:ref:`~PyQt5.QtCore.QRect` = QRect()
            mode: :sip:ref:`~PyQt5.QtCore.Qt.AspectRatioMode` = :sip:ref:`~PyQt5.QtCore.Qt.AspectRatioMode.KeepAspectRatio`
        :description: QtWidgets/QGraphicsView-render-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.renderHints
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPainter.RenderHints`
        :description: QtWidgets/QGraphicsView-renderHints-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.resetCachedContent
        :description: QtWidgets/QGraphicsView-resetCachedContent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.resetTransform
        :description: QtWidgets/QGraphicsView-resetTransform-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.resizeAnchor
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QGraphicsView.ViewportAnchor`
        :description: QtWidgets/QGraphicsView-resizeAnchor-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.resizeEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QResizeEvent`
        :description: QtWidgets/QGraphicsView-resizeEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.rotate
        :args:
            float
        :description: QtWidgets/QGraphicsView-rotate-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.rubberBandRect
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRect`
        :description: QtWidgets/QGraphicsView-rubberBandRect-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.rubberBandSelectionMode
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.ItemSelectionMode`
        :description: QtWidgets/QGraphicsView-rubberBandSelectionMode-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.scale
        :args:
            float
            float
        :description: QtWidgets/QGraphicsView-scale-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.scene
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QGraphicsScene`
        :description: QtWidgets/QGraphicsView-scene-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.sceneRect
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRectF`
        :description: QtWidgets/QGraphicsView-sceneRect-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.scrollContentsBy
        :args:
            int
            int
        :description: QtWidgets/QGraphicsView-scrollContentsBy-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.setAlignment
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.Qt.Alignment`, :sip:ref:`~PyQt5.QtCore.Qt.AlignmentFlag`]
        :description: QtWidgets/QGraphicsView-setAlignment-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.setBackgroundBrush
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QBrush`, :sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`, :sip:ref:`~PyQt5.QtGui.QGradient`]
        :description: QtWidgets/QGraphicsView-setBackgroundBrush-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.setCacheMode
        :args:
            Union[:sip:ref:`~PyQt5.QtWidgets.QGraphicsView.CacheMode`, :sip:ref:`~PyQt5.QtWidgets.QGraphicsView.CacheModeFlag`]
        :description: QtWidgets/QGraphicsView-setCacheMode-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.setDragMode
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QGraphicsView.DragMode`
        :description: QtWidgets/QGraphicsView-setDragMode-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.setForegroundBrush
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QBrush`, :sip:ref:`~PyQt5.QtGui.QColor`, :sip:ref:`~PyQt5.QtCore.Qt.GlobalColor`, :sip:ref:`~PyQt5.QtGui.QGradient`]
        :description: QtWidgets/QGraphicsView-setForegroundBrush-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.setInteractive
        :args:
            bool
        :description: QtWidgets/QGraphicsView-setInteractive-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.setOptimizationFlag
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QGraphicsView.OptimizationFlag`
            enabled: bool = True
        :description: QtWidgets/QGraphicsView-setOptimizationFlag-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.setOptimizationFlags
        :args:
            Union[:sip:ref:`~PyQt5.QtWidgets.QGraphicsView.OptimizationFlags`, :sip:ref:`~PyQt5.QtWidgets.QGraphicsView.OptimizationFlag`]
        :description: QtWidgets/QGraphicsView-setOptimizationFlags-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.setRenderHint
        :args:
            :sip:ref:`~PyQt5.QtGui.QPainter.RenderHint`
            on: bool = True
        :description: QtWidgets/QGraphicsView-setRenderHint-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.setRenderHints
        :args:
            Union[:sip:ref:`~PyQt5.QtGui.QPainter.RenderHints`, :sip:ref:`~PyQt5.QtGui.QPainter.RenderHint`]
        :description: QtWidgets/QGraphicsView-setRenderHints-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.setResizeAnchor
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QGraphicsView.ViewportAnchor`
        :description: QtWidgets/QGraphicsView-setResizeAnchor-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.setRubberBandSelectionMode
        :args:
            :sip:ref:`~PyQt5.QtCore.Qt.ItemSelectionMode`
        :description: QtWidgets/QGraphicsView-setRubberBandSelectionMode-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.setScene
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QGraphicsScene`
        :description: QtWidgets/QGraphicsView-setScene-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.setSceneRect
        :args:
            :sip:ref:`~PyQt5.QtCore.QRectF`
        :description: QtWidgets/QGraphicsView-setSceneRect-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.setSceneRect
        :args:
            float
            float
            float
            float
        :description: QtWidgets/QGraphicsView-setSceneRect-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.setTransform
        :args:
            :sip:ref:`~PyQt5.QtGui.QTransform`
            combine: bool = False
        :description: QtWidgets/QGraphicsView-setTransform-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.setTransformationAnchor
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QGraphicsView.ViewportAnchor`
        :description: QtWidgets/QGraphicsView-setTransformationAnchor-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.setupViewport
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QWidget`
        :description: QtWidgets/QGraphicsView-setupViewport-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.setViewportUpdateMode
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QGraphicsView.ViewportUpdateMode`
        :description: QtWidgets/QGraphicsView-setViewportUpdateMode-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.shear
        :args:
            float
            float
        :description: QtWidgets/QGraphicsView-shear-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.showEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QShowEvent`
        :description: QtWidgets/QGraphicsView-showEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.sizeHint
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtWidgets/QGraphicsView-sizeHint-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.transform
        :returns:
            :sip:ref:`~PyQt5.QtGui.QTransform`
        :description: QtWidgets/QGraphicsView-transform-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.transformationAnchor
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QGraphicsView.ViewportAnchor`
        :description: QtWidgets/QGraphicsView-transformationAnchor-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.translate
        :args:
            float
            float
        :description: QtWidgets/QGraphicsView-translate-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.updateScene
        :args:
            Iterable[:sip:ref:`~PyQt5.QtCore.QRectF`]
        :description: QtWidgets/QGraphicsView-updateScene-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.updateSceneRect
        :args:
            :sip:ref:`~PyQt5.QtCore.QRectF`
        :description: QtWidgets/QGraphicsView-updateSceneRect-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.viewportEvent
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtWidgets/QGraphicsView-viewportEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.viewportTransform
        :returns:
            :sip:ref:`~PyQt5.QtGui.QTransform`
        :description: QtWidgets/QGraphicsView-viewportTransform-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.viewportUpdateMode
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QGraphicsView.ViewportUpdateMode`
        :description: QtWidgets/QGraphicsView-viewportUpdateMode-f.rst

    .. sip:method:: PyQt5.QtWidgets.QGraphicsView.wheelEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QWheelEvent`
        :description: QtWidgets/QGraphicsView-wheelEvent-f.rst

    .. sip:signal:: PyQt5.QtWidgets.QGraphicsView.rubberBandChanged
        :args:
            :sip:ref:`~PyQt5.QtCore.QRect`
            Union[:sip:ref:`~PyQt5.QtCore.QPointF`, :sip:ref:`~PyQt5.QtCore.QPoint`]
            Union[:sip:ref:`~PyQt5.QtCore.QPointF`, :sip:ref:`~PyQt5.QtCore.QPoint`]
        :description: QtWidgets/QGraphicsView-rubberBandChanged-s.rst
