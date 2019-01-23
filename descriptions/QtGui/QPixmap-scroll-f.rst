.. sip:method-description::
    :status: todo
    :pysig: 6d4f7c4d65b67381901bc5678b45615b
    :realsig: (int,int,const QRect&,QRegion*)
    :digest: 296886ae92103d3c0f4c5a60c67b3874

Scrolls the area *rect* of this pixmap by (\ *dx*, *dy*). The exposed region is left unchanged. You can optionally pass a pointer to an empty :sip:ref:`~PyQt5.QtGui.QRegion` to get the region that is *exposed* by the scroll operation.

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-code-src_gui_image_qpixmap.py
    :lines: 67-69

You cannot scroll while there is an active painter on the pixmap.

.. seealso:: :sip:ref:`~PyQt5.QtWidgets.QWidget.scroll`.
