.. sip:method-description::
    :status: todo
    :pysig: a5d6209f8edbccf59a49f1bee023df74
    :realsig: (const QMarginsF&)
    :digest: 8816ef1353ff409dc1754d9d846210a8

Sets the page margins of the page layout to *margins* Returns true if the margins were successfully set.

The units used are those currently defined for the layout. To use different units then call :sip:ref:`~PyQt5.QtGui.QPageLayout.setUnits` first.

If in the default :sip:ref:`~PyQt5.QtGui.QPageLayout.Mode.StandardMode` then all the new margins must fall between the minimum margins set and the maximum margins allowed by the page size, otherwise the margins will not be set.

If in :sip:ref:`~PyQt5.QtGui.QPageLayout.Mode.FullPageMode` then any margin values will be accepted.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPageLayout.margins`, :sip:ref:`~PyQt5.QtGui.QPageLayout.units`.
