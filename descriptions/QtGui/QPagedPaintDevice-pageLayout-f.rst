.. sip:method-description::
    :status: todo
    :pysig: e8337d6678275538543450208e8cbf7c
    :realsig: () const
    :digest: 47b83fc534bf8599c2ca17f8f4e1eb3a

Returns the current page layout. Use this method to access the current :sip:ref:`~PyQt5.QtGui.QPageSize`, :sip:ref:`~PyQt5.QtGui.QPageLayout.Orientation`, :sip:ref:`~PyQt5.QtCore.QMarginsF`, fullRect() and paintRect().

Note that you cannot use the setters on the returned object, you must either call the individual :sip:ref:`~PyQt5.QtGui.QPagedPaintDevice` setters or use :sip:ref:`~PyQt5.QtGui.QPagedPaintDevice.setPageLayout`.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPagedPaintDevice.setPageLayout`, :sip:ref:`~PyQt5.QtGui.QPagedPaintDevice.setPageSize`, :sip:ref:`~PyQt5.QtGui.QPagedPaintDevice.setPageOrientation`, :sip:ref:`~PyQt5.QtGui.QPagedPaintDevice.setPageMargins`.
