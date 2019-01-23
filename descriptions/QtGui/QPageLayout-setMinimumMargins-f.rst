.. sip:method-description::
    :status: todo
    :pysig: 1c62012a40cb5f31f07d5aa6e1bfb7e2
    :realsig: (const QMarginsF&)
    :digest: 3e7ae6544030ee25b9ab9bb6e6ec932a

Sets the minimum page margins of the page layout to *minMargins*.

It is not recommended to override the default values set for a page size as this may be the minimum printable area for a physical print device.

If the :sip:ref:`~PyQt5.QtGui.QPageLayout.Mode.StandardMode` mode is set then the existing margins will be clamped to the new *minMargins* and the maximum allowed by the page size. If the :sip:ref:`~PyQt5.QtGui.QPageLayout.Mode.FullPageMode` is set then the existing margins will be unchanged.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPageLayout.minimumMargins`, :sip:ref:`~PyQt5.QtGui.QPageLayout.setMargins`.
