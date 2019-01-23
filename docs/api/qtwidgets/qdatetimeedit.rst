:orphan:

.. sip:class:: PyQt5.QtWidgets.QDateTimeEdit
    :inherits: :sip:ref:`~PyQt5.QtWidgets.QAbstractSpinBox`
    :description: QtWidgets/QDateTimeEdit-c.rst

    .. sip:enum:: PyQt5.QtWidgets.QDateTimeEdit.Section
        :description: QtWidgets/QDateTimeEdit-Section-e.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QDateTimeEdit.Section.AmPmSection
            :description: QtWidgets/QDateTimeEdit-Section-AmPmSection-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QDateTimeEdit.Section.DateSections_Mask
            :description: QtWidgets/QDateTimeEdit-Section-DateSections_Mask-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QDateTimeEdit.Section.DaySection
            :description: QtWidgets/QDateTimeEdit-Section-DaySection-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QDateTimeEdit.Section.HourSection
            :description: QtWidgets/QDateTimeEdit-Section-HourSection-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QDateTimeEdit.Section.MinuteSection
            :description: QtWidgets/QDateTimeEdit-Section-MinuteSection-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QDateTimeEdit.Section.MonthSection
            :description: QtWidgets/QDateTimeEdit-Section-MonthSection-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QDateTimeEdit.Section.MSecSection
            :description: QtWidgets/QDateTimeEdit-Section-MSecSection-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QDateTimeEdit.Section.NoSection
            :description: QtWidgets/QDateTimeEdit-Section-NoSection-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QDateTimeEdit.Section.SecondSection
            :description: QtWidgets/QDateTimeEdit-Section-SecondSection-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QDateTimeEdit.Section.TimeSections_Mask
            :description: QtWidgets/QDateTimeEdit-Section-TimeSections_Mask-v.rst

        .. sip:enum-member:: PyQt5.QtWidgets.QDateTimeEdit.Section.YearSection
            :description: QtWidgets/QDateTimeEdit-Section-YearSection-v.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
        :description: QtWidgets/QDateTimeEdit-__init__-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.__init__
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QDateTime`, datetime.datetime]
            parent: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
        :description: QtWidgets/QDateTimeEdit-__init__-f-1.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.__init__
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QDate`, datetime.date]
            parent: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
        :description: QtWidgets/QDateTimeEdit-__init__-f-2.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.__init__
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QTime`, datetime.time]
            parent: :sip:ref:`~PyQt5.QtWidgets.QWidget` = None
        :description: QtWidgets/QDateTimeEdit-__init__-f-3.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.calendarPopup
        :returns:
            bool
        :description: QtWidgets/QDateTimeEdit-calendarPopup-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.calendarWidget
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QCalendarWidget`
        :description: QtWidgets/QDateTimeEdit-calendarWidget-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.clear
        :description: QtWidgets/QDateTimeEdit-clear-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.clearMaximumDate
        :description: QtWidgets/QDateTimeEdit-clearMaximumDate-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.clearMaximumDateTime
        :description: QtWidgets/QDateTimeEdit-clearMaximumDateTime-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.clearMaximumTime
        :description: QtWidgets/QDateTimeEdit-clearMaximumTime-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.clearMinimumDate
        :description: QtWidgets/QDateTimeEdit-clearMinimumDate-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.clearMinimumDateTime
        :description: QtWidgets/QDateTimeEdit-clearMinimumDateTime-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.clearMinimumTime
        :description: QtWidgets/QDateTimeEdit-clearMinimumTime-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.currentSection
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QDateTimeEdit.Section`
        :description: QtWidgets/QDateTimeEdit-currentSection-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.currentSectionIndex
        :returns:
            int
        :description: QtWidgets/QDateTimeEdit-currentSectionIndex-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.date
        :returns:
            :sip:ref:`~PyQt5.QtCore.QDate`
        :description: QtWidgets/QDateTimeEdit-date-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.dateTime
        :returns:
            :sip:ref:`~PyQt5.QtCore.QDateTime`
        :description: QtWidgets/QDateTimeEdit-dateTime-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.dateTimeFromText
        :args:
            str
        :returns:
            :sip:ref:`~PyQt5.QtCore.QDateTime`
        :description: QtWidgets/QDateTimeEdit-dateTimeFromText-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.displayedSections
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QDateTimeEdit.Sections`
        :description: QtWidgets/QDateTimeEdit-displayedSections-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.displayFormat
        :returns:
            str
        :description: QtWidgets/QDateTimeEdit-displayFormat-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.event
        :args:
            :sip:ref:`~PyQt5.QtCore.QEvent`
        :returns:
            bool
        :description: QtWidgets/QDateTimeEdit-event-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.fixup
        :args:
            str
        :returns:
            str
        :description: QtWidgets/QDateTimeEdit-fixup-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.focusInEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QFocusEvent`
        :description: QtWidgets/QDateTimeEdit-focusInEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.focusNextPrevChild
        :args:
            bool
        :returns:
            bool
        :description: QtWidgets/QDateTimeEdit-focusNextPrevChild-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.initStyleOption
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QStyleOptionSpinBox`
        :description: QtWidgets/QDateTimeEdit-initStyleOption-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.keyPressEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QKeyEvent`
        :description: QtWidgets/QDateTimeEdit-keyPressEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.maximumDate
        :returns:
            :sip:ref:`~PyQt5.QtCore.QDate`
        :description: QtWidgets/QDateTimeEdit-maximumDate-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.maximumDateTime
        :returns:
            :sip:ref:`~PyQt5.QtCore.QDateTime`
        :description: QtWidgets/QDateTimeEdit-maximumDateTime-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.maximumTime
        :returns:
            :sip:ref:`~PyQt5.QtCore.QTime`
        :description: QtWidgets/QDateTimeEdit-maximumTime-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.minimumDate
        :returns:
            :sip:ref:`~PyQt5.QtCore.QDate`
        :description: QtWidgets/QDateTimeEdit-minimumDate-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.minimumDateTime
        :returns:
            :sip:ref:`~PyQt5.QtCore.QDateTime`
        :description: QtWidgets/QDateTimeEdit-minimumDateTime-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.minimumTime
        :returns:
            :sip:ref:`~PyQt5.QtCore.QTime`
        :description: QtWidgets/QDateTimeEdit-minimumTime-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.mousePressEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QMouseEvent`
        :description: QtWidgets/QDateTimeEdit-mousePressEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.paintEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QPaintEvent`
        :description: QtWidgets/QDateTimeEdit-paintEvent-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.sectionAt
        :args:
            int
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QDateTimeEdit.Section`
        :description: QtWidgets/QDateTimeEdit-sectionAt-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.sectionCount
        :returns:
            int
        :description: QtWidgets/QDateTimeEdit-sectionCount-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.sectionText
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QDateTimeEdit.Section`
        :returns:
            str
        :description: QtWidgets/QDateTimeEdit-sectionText-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.setCalendarPopup
        :args:
            bool
        :description: QtWidgets/QDateTimeEdit-setCalendarPopup-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.setCalendarWidget
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QCalendarWidget`
        :description: QtWidgets/QDateTimeEdit-setCalendarWidget-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.setCurrentSection
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QDateTimeEdit.Section`
        :description: QtWidgets/QDateTimeEdit-setCurrentSection-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.setCurrentSectionIndex
        :args:
            int
        :description: QtWidgets/QDateTimeEdit-setCurrentSectionIndex-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.setDate
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QDate`, datetime.date]
        :description: QtWidgets/QDateTimeEdit-setDate-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.setDateRange
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QDate`, datetime.date]
            Union[:sip:ref:`~PyQt5.QtCore.QDate`, datetime.date]
        :description: QtWidgets/QDateTimeEdit-setDateRange-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.setDateTime
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QDateTime`, datetime.datetime]
        :description: QtWidgets/QDateTimeEdit-setDateTime-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.setDateTimeRange
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QDateTime`, datetime.datetime]
            Union[:sip:ref:`~PyQt5.QtCore.QDateTime`, datetime.datetime]
        :description: QtWidgets/QDateTimeEdit-setDateTimeRange-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.setDisplayFormat
        :args:
            str
        :description: QtWidgets/QDateTimeEdit-setDisplayFormat-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.setMaximumDate
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QDate`, datetime.date]
        :description: QtWidgets/QDateTimeEdit-setMaximumDate-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.setMaximumDateTime
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QDateTime`, datetime.datetime]
        :description: QtWidgets/QDateTimeEdit-setMaximumDateTime-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.setMaximumTime
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QTime`, datetime.time]
        :description: QtWidgets/QDateTimeEdit-setMaximumTime-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.setMinimumDate
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QDate`, datetime.date]
        :description: QtWidgets/QDateTimeEdit-setMinimumDate-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.setMinimumDateTime
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QDateTime`, datetime.datetime]
        :description: QtWidgets/QDateTimeEdit-setMinimumDateTime-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.setMinimumTime
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QTime`, datetime.time]
        :description: QtWidgets/QDateTimeEdit-setMinimumTime-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.setSelectedSection
        :args:
            :sip:ref:`~PyQt5.QtWidgets.QDateTimeEdit.Section`
        :description: QtWidgets/QDateTimeEdit-setSelectedSection-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.setTime
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QTime`, datetime.time]
        :description: QtWidgets/QDateTimeEdit-setTime-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.setTimeRange
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QTime`, datetime.time]
            Union[:sip:ref:`~PyQt5.QtCore.QTime`, datetime.time]
        :description: QtWidgets/QDateTimeEdit-setTimeRange-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.setTimeSpec
        :args:
            :sip:ref:`~PyQt5.QtCore.Qt.TimeSpec`
        :description: QtWidgets/QDateTimeEdit-setTimeSpec-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.sizeHint
        :returns:
            :sip:ref:`~PyQt5.QtCore.QSize`
        :description: QtWidgets/QDateTimeEdit-sizeHint-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.stepBy
        :args:
            int
        :description: QtWidgets/QDateTimeEdit-stepBy-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.stepEnabled
        :returns:
            :sip:ref:`~PyQt5.QtWidgets.QAbstractSpinBox.StepEnabled`
        :description: QtWidgets/QDateTimeEdit-stepEnabled-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.textFromDateTime
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QDateTime`, datetime.datetime]
        :returns:
            str
        :description: QtWidgets/QDateTimeEdit-textFromDateTime-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.time
        :returns:
            :sip:ref:`~PyQt5.QtCore.QTime`
        :description: QtWidgets/QDateTimeEdit-time-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.timeSpec
        :returns:
            :sip:ref:`~PyQt5.QtCore.Qt.TimeSpec`
        :description: QtWidgets/QDateTimeEdit-timeSpec-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.validate
        :args:
            str
            int
        :returns:
            :sip:ref:`~PyQt5.QtGui.QValidator.State`
            str
            int
        :description: QtWidgets/QDateTimeEdit-validate-f.rst

    .. sip:method:: PyQt5.QtWidgets.QDateTimeEdit.wheelEvent
        :args:
            :sip:ref:`~PyQt5.QtGui.QWheelEvent`
        :description: QtWidgets/QDateTimeEdit-wheelEvent-f.rst

    .. sip:signal:: PyQt5.QtWidgets.QDateTimeEdit.dateChanged
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QDate`, datetime.date]
        :description: QtWidgets/QDateTimeEdit-dateChanged-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QDateTimeEdit.dateTimeChanged
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QDateTime`, datetime.datetime]
        :description: QtWidgets/QDateTimeEdit-dateTimeChanged-s.rst

    .. sip:signal:: PyQt5.QtWidgets.QDateTimeEdit.timeChanged
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QTime`, datetime.time]
        :description: QtWidgets/QDateTimeEdit-timeChanged-s.rst
