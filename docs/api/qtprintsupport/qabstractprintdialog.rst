:orphan:

.. sip:class:: PyQt5.QtPrintSupport.QAbstractPrintDialog
    :inherits: :sip:ref:`~PyQt5.QtWidgets.QDialog`
    :description: QtPrintSupport/QAbstractPrintDialog-c.rst

    .. sip:enum:: PyQt5.QtPrintSupport.QAbstractPrintDialog.PrintDialogOption
        :description: QtPrintSupport/QAbstractPrintDialog-PrintDialogOption-e.rst

        .. sip:enum-member:: PyQt5.QtPrintSupport.QAbstractPrintDialog.PrintDialogOption.None_
            :description: QtPrintSupport/QAbstractPrintDialog-PrintDialogOption-None_-v.rst

        .. sip:enum-member:: PyQt5.QtPrintSupport.QAbstractPrintDialog.PrintDialogOption.PrintCollateCopies
            :description: QtPrintSupport/QAbstractPrintDialog-PrintDialogOption-PrintCollateCopies-v.rst

        .. sip:enum-member:: PyQt5.QtPrintSupport.QAbstractPrintDialog.PrintDialogOption.PrintCurrentPage
            :description: QtPrintSupport/QAbstractPrintDialog-PrintDialogOption-PrintCurrentPage-v.rst

        .. sip:enum-member:: PyQt5.QtPrintSupport.QAbstractPrintDialog.PrintDialogOption.PrintPageRange
            :description: QtPrintSupport/QAbstractPrintDialog-PrintDialogOption-PrintPageRange-v.rst

        .. sip:enum-member:: PyQt5.QtPrintSupport.QAbstractPrintDialog.PrintDialogOption.PrintSelection
            :description: QtPrintSupport/QAbstractPrintDialog-PrintDialogOption-PrintSelection-v.rst

        .. sip:enum-member:: PyQt5.QtPrintSupport.QAbstractPrintDialog.PrintDialogOption.PrintShowPageSize
            :description: QtPrintSupport/QAbstractPrintDialog-PrintDialogOption-PrintShowPageSize-v.rst

        .. sip:enum-member:: PyQt5.QtPrintSupport.QAbstractPrintDialog.PrintDialogOption.PrintToFile
            :description: QtPrintSupport/QAbstractPrintDialog-PrintDialogOption-PrintToFile-v.rst

    .. sip:enum:: PyQt5.QtPrintSupport.QAbstractPrintDialog.PrintRange
        :description: QtPrintSupport/QAbstractPrintDialog-PrintRange-e.rst

        .. sip:enum-member:: PyQt5.QtPrintSupport.QAbstractPrintDialog.PrintRange.AllPages
            :description: QtPrintSupport/QAbstractPrintDialog-PrintRange-AllPages-v.rst

        .. sip:enum-member:: PyQt5.QtPrintSupport.QAbstractPrintDialog.PrintRange.CurrentPage
            :description: QtPrintSupport/QAbstractPrintDialog-PrintRange-CurrentPage-v.rst

        .. sip:enum-member:: PyQt5.QtPrintSupport.QAbstractPrintDialog.PrintRange.PageRange
            :description: QtPrintSupport/QAbstractPrintDialog-PrintRange-PageRange-v.rst

        .. sip:enum-member:: PyQt5.QtPrintSupport.QAbstractPrintDialog.PrintRange.Selection
            :description: QtPrintSupport/QAbstractPrintDialog-PrintRange-Selection-v.rst

    .. sip:method:: PyQt5.QtPrintSupport.QAbstractPrintDialog.__init__
        :args:
            :sip:ref:`~PyQt5.QtPrintSupport.QPrinter`
            parent: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
        :description: QtPrintSupport/QAbstractPrintDialog-__init__-f.rst

    .. sip:method:: PyQt5.QtPrintSupport.QAbstractPrintDialog.enabledOptions
        :returns:
            :sip:ref:`~PyQt5.QtPrintSupport.QAbstractPrintDialog.PrintDialogOptions`
        :description: QtPrintSupport/QAbstractPrintDialog-enabledOptions-f.rst

    .. sip:method:: PyQt5.QtPrintSupport.QAbstractPrintDialog.exec
        :returns:
            int
        :description: QtPrintSupport/QAbstractPrintDialog-exec-f.rst

    .. sip:method:: PyQt5.QtPrintSupport.QAbstractPrintDialog.exec_
        :returns:
            int
        :description: QtPrintSupport/QAbstractPrintDialog-exec_-f.rst

    .. sip:method:: PyQt5.QtPrintSupport.QAbstractPrintDialog.fromPage
        :returns:
            int
        :description: QtPrintSupport/QAbstractPrintDialog-fromPage-f.rst

    .. sip:method:: PyQt5.QtPrintSupport.QAbstractPrintDialog.maxPage
        :returns:
            int
        :description: QtPrintSupport/QAbstractPrintDialog-maxPage-f.rst

    .. sip:method:: PyQt5.QtPrintSupport.QAbstractPrintDialog.minPage
        :returns:
            int
        :description: QtPrintSupport/QAbstractPrintDialog-minPage-f.rst

    .. sip:method:: PyQt5.QtPrintSupport.QAbstractPrintDialog.printer
        :returns:
            :sip:ref:`~PyQt5.QtPrintSupport.QPrinter`
        :description: QtPrintSupport/QAbstractPrintDialog-printer-f.rst

    .. sip:method:: PyQt5.QtPrintSupport.QAbstractPrintDialog.printRange
        :returns:
            :sip:ref:`~PyQt5.QtPrintSupport.QAbstractPrintDialog.PrintRange`
        :description: QtPrintSupport/QAbstractPrintDialog-printRange-f.rst

    .. sip:method:: PyQt5.QtPrintSupport.QAbstractPrintDialog.setEnabledOptions
        :args:
            Union[:sip:ref:`~PyQt5.QtPrintSupport.QAbstractPrintDialog.PrintDialogOptions`, :sip:ref:`~PyQt5.QtPrintSupport.QAbstractPrintDialog.PrintDialogOption`]
        :description: QtPrintSupport/QAbstractPrintDialog-setEnabledOptions-f.rst

    .. sip:method:: PyQt5.QtPrintSupport.QAbstractPrintDialog.setFromTo
        :args:
            int
            int
        :description: QtPrintSupport/QAbstractPrintDialog-setFromTo-f.rst

    .. sip:method:: PyQt5.QtPrintSupport.QAbstractPrintDialog.setMinMax
        :args:
            int
            int
        :description: QtPrintSupport/QAbstractPrintDialog-setMinMax-f.rst

    .. sip:method:: PyQt5.QtPrintSupport.QAbstractPrintDialog.setOptionTabs
        :args:
            Iterable[:sip:ref:`~PyQt5.QtWidgets.QWidget`]
        :description: QtPrintSupport/QAbstractPrintDialog-setOptionTabs-f.rst

    .. sip:method:: PyQt5.QtPrintSupport.QAbstractPrintDialog.setPrintRange
        :args:
            :sip:ref:`~PyQt5.QtPrintSupport.QAbstractPrintDialog.PrintRange`
        :description: QtPrintSupport/QAbstractPrintDialog-setPrintRange-f.rst

    .. sip:method:: PyQt5.QtPrintSupport.QAbstractPrintDialog.toPage
        :returns:
            int
        :description: QtPrintSupport/QAbstractPrintDialog-toPage-f.rst
