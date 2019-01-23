.. sip:class-description::
    :status: todo
    :brief: QGraphicsItem that can be used to render the contents of SVG files
    :digest: d5ef7b3fbd00f9cccff16b3158ab9d33

The :sip:ref:`~PyQt5.QtSvg.QGraphicsSvgItem` class is a QGraphicsItem that can be used to render the contents of SVG files.

:sip:ref:`~PyQt5.QtSvg.QGraphicsSvgItem` provides a way of rendering SVG files onto QGraphicsView. :sip:ref:`~PyQt5.QtSvg.QGraphicsSvgItem` can be created by passing the SVG file to be rendered to its constructor or by explicit setting a shared :sip:ref:`~PyQt5.QtSvg.QSvgRenderer` on it.

Note that setting :sip:ref:`~PyQt5.QtSvg.QSvgRenderer` on a :sip:ref:`~PyQt5.QtSvg.QGraphicsSvgItem` doesn't make the item take ownership of the renderer, therefore if using  method one has to make sure that the lifetime of the :sip:ref:`~PyQt5.QtSvg.QSvgRenderer` object will be at least as long as that of the :sip:ref:`~PyQt5.QtSvg.QGraphicsSvgItem`.

:sip:ref:`~PyQt5.QtSvg.QGraphicsSvgItem` provides a way of rendering only parts of the SVG files via the setElementId. If  method is called, only the SVG element (and its children) with the passed id will be renderer. This provides a convenient way of selectively rendering large SVG files that contain a number of discrete elements. For example the following code renders only jokers from a SVG file containing a whole card deck:

.. literalinclude:: ../../../snippets/qtsvg-src-svg-doc-snippets-src_svg_qgraphicssvgitem.py
    :lines: 54-62

Size of the item can be set via direct manipulation of the items transformation matrix.

By default the SVG rendering is cached using QGraphicsItem::DeviceCoordinateCache mode to speedup the display of items. Caching can be disabled by passing QGraphicsItem::NoCache to the QGraphicsItem::setCacheMode() method.

.. seealso:: :sip:ref:`~PyQt5.QtSvg.QSvgWidget`, :sip:ref:`~PyQt5.Qt SVG C++ Classes`.
