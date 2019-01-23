.. sip:enum-description::
    :status: todo
    :digest: 5e1ce0792137e2f806c7a5b7daa0c345

This enum type lists the available page sizes as defined in the Postscript PPD standard. These values are duplicated in :sip:ref:`~PyQt5.QtGui.QPageSize` and QPrinter.

The defined sizes are:

Due to historic reasons :sip:ref:`~PyQt5.QtGui.QPageSize.PageSizeId.Executive` is not the same as the standard Postscript and Windows Executive size, use :sip:ref:`~PyQt5.QtGui.QPageSize.PageSizeId.ExecutiveStandard` instead.

The Postscript standard size :sip:ref:`~PyQt5.QtGui.QPageSize.PageSizeId.Folio` is different to the Windows DMPAPER_FOLIO size, use the Postscript standard size :sip:ref:`~PyQt5.QtGui.QPageSize.PageSizeId.FanFoldGermanLegal` if needed.
