:orphan:

.. sip:class:: PyQt5.QtGui.QAbstractTextDocumentLayout
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtGui/QAbstractTextDocumentLayout-c.rst

    .. sip:method:: PyQt5.QtGui.QAbstractTextDocumentLayout.__init__
        :args:
            :sip:ref:`~PyQt5.QtGui.QTextDocument`
        :description: QtGui/QAbstractTextDocumentLayout-__init__-f.rst

    .. sip:method:: PyQt5.QtGui.QAbstractTextDocumentLayout.anchorAt
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QPointF`, :sip:ref:`~PyQt5.QtCore.QPoint`]
        :returns:
            str
        :description: QtGui/QAbstractTextDocumentLayout-anchorAt-f.rst

    .. sip:method:: PyQt5.QtGui.QAbstractTextDocumentLayout.blockBoundingRect
        :args:
            :sip:ref:`~PyQt5.QtGui.QTextBlock`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRectF`
        :description: QtGui/QAbstractTextDocumentLayout-blockBoundingRect-f.rst

    .. sip:method:: PyQt5.QtGui.QAbstractTextDocumentLayout.blockWithMarkerAt
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QPointF`, :sip:ref:`~PyQt5.QtCore.QPoint`]
        :returns:
            :sip:ref:`~PyQt5.QtGui.QTextBlock`
        :description: QtGui/QAbstractTextDocumentLayout-blockWithMarkerAt-f.rst

    .. sip:method:: PyQt5.QtGui.QAbstractTextDocumentLayout.document
        :returns:
            :sip:ref:`~PyQt5.QtGui.QTextDocument`
        :description: QtGui/QAbstractTextDocumentLayout-document-f.rst

    .. sip:method:: PyQt5.QtGui.QAbstractTextDocumentLayout.documentChanged
        :args:
            int
            int
            int
        :description: QtGui/QAbstractTextDocumentLayout-documentChanged-f.rst

    .. sip:method:: PyQt5.QtGui.QAbstractTextDocumentLayout.documentSize
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSizeF`
        :description: QtGui/QAbstractTextDocumentLayout-documentSize-f.rst

    .. sip:method:: PyQt5.QtGui.QAbstractTextDocumentLayout.draw
        :args:
            :sip:ref:`~PyQt5.QtGui.QPainter`
            :sip:ref:`~PyQt5.QtGui.QAbstractTextDocumentLayout.PaintContext`
        :description: QtGui/QAbstractTextDocumentLayout-draw-f.rst

    .. sip:method:: PyQt5.QtGui.QAbstractTextDocumentLayout.drawInlineObject
        :args:
            :sip:ref:`~PyQt5.QtGui.QPainter`
            :sip:ref:`~PyQt5.QtCore.QRectF`
            :sip:ref:`~PyQt5.QtGui.QTextInlineObject`
            int
            :sip:ref:`~PyQt5.QtGui.QTextFormat`
        :description: QtGui/QAbstractTextDocumentLayout-drawInlineObject-f.rst

    .. sip:method:: PyQt5.QtGui.QAbstractTextDocumentLayout.format
        :args:
            int
        :returns:
            :sip:ref:`~PyQt5.QtGui.QTextCharFormat`
        :description: QtGui/QAbstractTextDocumentLayout-format-f.rst

    .. sip:method:: PyQt5.QtGui.QAbstractTextDocumentLayout.formatAt
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QPointF`, :sip:ref:`~PyQt5.QtCore.QPoint`]
        :returns:
            :sip:ref:`~PyQt5.QtGui.QTextFormat`
        :description: QtGui/QAbstractTextDocumentLayout-formatAt-f.rst

    .. sip:method:: PyQt5.QtGui.QAbstractTextDocumentLayout.frameBoundingRect
        :args:
            :sip:ref:`~PyQt5.QtGui.QTextFrame`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QRectF`
        :description: QtGui/QAbstractTextDocumentLayout-frameBoundingRect-f.rst

    .. sip:method:: PyQt5.QtGui.QAbstractTextDocumentLayout.handlerForObject
        :args:
            int
        :returns:
            :sip:ref:`~PyQt5.QtGui.QTextObjectInterface`
        :description: QtGui/QAbstractTextDocumentLayout-handlerForObject-f.rst

    .. sip:method:: PyQt5.QtGui.QAbstractTextDocumentLayout.hitTest
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QPointF`, :sip:ref:`~PyQt5.QtCore.QPoint`]
            :sip:ref:`~PyQt5.QtCore.Qt.HitTestAccuracy`
        :returns:
            int
        :description: QtGui/QAbstractTextDocumentLayout-hitTest-f.rst

    .. sip:method:: PyQt5.QtGui.QAbstractTextDocumentLayout.imageAt
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QPointF`, :sip:ref:`~PyQt5.QtCore.QPoint`]
        :returns:
            str
        :description: QtGui/QAbstractTextDocumentLayout-imageAt-f.rst

    .. sip:method:: PyQt5.QtGui.QAbstractTextDocumentLayout.pageCount
        :returns:
            int
        :description: QtGui/QAbstractTextDocumentLayout-pageCount-f.rst

    .. sip:method:: PyQt5.QtGui.QAbstractTextDocumentLayout.paintDevice
        :returns:
            :sip:ref:`~PyQt5.QtGui.QPaintDevice`
        :description: QtGui/QAbstractTextDocumentLayout-paintDevice-f.rst

    .. sip:method:: PyQt5.QtGui.QAbstractTextDocumentLayout.positionInlineObject
        :args:
            :sip:ref:`~PyQt5.QtGui.QTextInlineObject`
            int
            :sip:ref:`~PyQt5.QtGui.QTextFormat`
        :description: QtGui/QAbstractTextDocumentLayout-positionInlineObject-f.rst

    .. sip:method:: PyQt5.QtGui.QAbstractTextDocumentLayout.registerHandler
        :args:
            int
            :sip:ref:`~PyQt5.QtCore.QObject`
        :description: QtGui/QAbstractTextDocumentLayout-registerHandler-f.rst

    .. sip:method:: PyQt5.QtGui.QAbstractTextDocumentLayout.resizeInlineObject
        :args:
            :sip:ref:`~PyQt5.QtGui.QTextInlineObject`
            int
            :sip:ref:`~PyQt5.QtGui.QTextFormat`
        :description: QtGui/QAbstractTextDocumentLayout-resizeInlineObject-f.rst

    .. sip:method:: PyQt5.QtGui.QAbstractTextDocumentLayout.setPaintDevice
        :args:
            :sip:ref:`~PyQt5.QtGui.QPaintDevice`
        :description: QtGui/QAbstractTextDocumentLayout-setPaintDevice-f.rst

    .. sip:method:: PyQt5.QtGui.QAbstractTextDocumentLayout.unregisterHandler
        :args:
            int
            component: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtGui/QAbstractTextDocumentLayout-unregisterHandler-f.rst

    .. sip:signal:: PyQt5.QtGui.QAbstractTextDocumentLayout.documentSizeChanged
        :args:
            :sip:ref:`~PyQt5.QtCore.QSizeF`
        :description: QtGui/QAbstractTextDocumentLayout-documentSizeChanged-s.rst

    .. sip:signal:: PyQt5.QtGui.QAbstractTextDocumentLayout.pageCountChanged
        :args:
            int
        :description: QtGui/QAbstractTextDocumentLayout-pageCountChanged-s.rst

    .. sip:signal:: PyQt5.QtGui.QAbstractTextDocumentLayout.update
        :args:
            rect: :sip:ref:`~PyQt5.QtCore.QRectF` = QRectF(0,0,1e+09,1e+09)
        :description: QtGui/QAbstractTextDocumentLayout-update-s.rst

    .. sip:signal:: PyQt5.QtGui.QAbstractTextDocumentLayout.updateBlock
        :args:
            :sip:ref:`~PyQt5.QtGui.QTextBlock`
        :description: QtGui/QAbstractTextDocumentLayout-updateBlock-s.rst
