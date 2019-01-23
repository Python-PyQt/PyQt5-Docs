:orphan:

.. sip:class:: PyQt5.QtCore.QDate
    :description: QtCore/QDate-c.rst

    .. sip:enum:: PyQt5.QtCore.QDate.MonthNameType
        :description: QtCore/QDate-MonthNameType-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QDate.MonthNameType.DateFormat
            :description: QtCore/QDate-MonthNameType-DateFormat-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QDate.MonthNameType.StandaloneFormat
            :description: QtCore/QDate-MonthNameType-StandaloneFormat-v.rst

    .. sip:method:: PyQt5.QtCore.QDate.__init__
        :description: QtCore/QDate-__init__-f.rst

    .. sip:method:: PyQt5.QtCore.QDate.__init__
        :args:
            :sip:ref:`~PyQt5.QtCore.QDate`
        :description: QtCore/QDate-__init__-f-1.rst

    .. sip:method:: PyQt5.QtCore.QDate.__init__
        :args:
            int
            int
            int
        :description: QtCore/QDate-__init__-f-2.rst

    .. sip:method:: PyQt5.QtCore.QDate.addDays
        :args:
            int
        :returns:
            :sip:ref:`~PyQt5.QtCore.QDate`
        :description: QtCore/QDate-addDays-f.rst

    .. sip:method:: PyQt5.QtCore.QDate.addMonths
        :args:
            int
        :returns:
            :sip:ref:`~PyQt5.QtCore.QDate`
        :description: QtCore/QDate-addMonths-f.rst

    .. sip:method:: PyQt5.QtCore.QDate.addYears
        :args:
            int
        :returns:
            :sip:ref:`~PyQt5.QtCore.QDate`
        :description: QtCore/QDate-addYears-f.rst

    .. sip:method:: PyQt5.QtCore.QDate.__bool__
        :returns:
            int
        :description: QtCore/QDate-__bool__-f.rst

    .. sip:method:: PyQt5.QtCore.QDate.currentDate
        :returns:
            :sip:ref:`~PyQt5.QtCore.QDate`
        :static:
        :description: QtCore/QDate-currentDate-f.rst

    .. sip:method:: PyQt5.QtCore.QDate.day
        :returns:
            int
        :description: QtCore/QDate-day-f.rst

    .. sip:method:: PyQt5.QtCore.QDate.dayOfWeek
        :returns:
            int
        :description: QtCore/QDate-dayOfWeek-f.rst

    .. sip:method:: PyQt5.QtCore.QDate.dayOfYear
        :returns:
            int
        :description: QtCore/QDate-dayOfYear-f.rst

    .. sip:method:: PyQt5.QtCore.QDate.daysInMonth
        :returns:
            int
        :description: QtCore/QDate-daysInMonth-f.rst

    .. sip:method:: PyQt5.QtCore.QDate.daysInYear
        :returns:
            int
        :description: QtCore/QDate-daysInYear-f.rst

    .. sip:method:: PyQt5.QtCore.QDate.daysTo
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QDate`, datetime.date]
        :returns:
            int
        :description: QtCore/QDate-daysTo-f.rst

    .. sip:method:: PyQt5.QtCore.QDate.__eq__
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QDate`, datetime.date]
        :returns:
            bool
        :description: QtCore/QDate-__eq__-f.rst

    .. sip:method:: PyQt5.QtCore.QDate.fromJulianDay
        :args:
            int
        :returns:
            :sip:ref:`~PyQt5.QtCore.QDate`
        :static:
        :description: QtCore/QDate-fromJulianDay-f.rst

    .. sip:method:: PyQt5.QtCore.QDate.fromString
        :args:
            str
            format: :sip:ref:`~PyQt5.QtCore.Qt.DateFormat` = :sip:ref:`~PyQt5.QtCore.Qt.DateFormat.TextDate`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QDate`
        :static:
        :description: QtCore/QDate-fromString-f.rst

    .. sip:method:: PyQt5.QtCore.QDate.fromString
        :args:
            str
            str
        :returns:
            :sip:ref:`~PyQt5.QtCore.QDate`
        :static:
        :description: QtCore/QDate-fromString-f-1.rst

    .. sip:method:: PyQt5.QtCore.QDate.__ge__
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QDate`, datetime.date]
        :returns:
            bool
        :description: QtCore/QDate-__ge__-f.rst

    .. sip:method:: PyQt5.QtCore.QDate.getDate
        :returns:
            int
            int
            int
        :description: QtCore/QDate-getDate-f.rst

    .. sip:method:: PyQt5.QtCore.QDate.__gt__
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QDate`, datetime.date]
        :returns:
            bool
        :description: QtCore/QDate-__gt__-f.rst

    .. sip:method:: PyQt5.QtCore.QDate.__hash__
        :returns:
            int
        :description: QtCore/QDate-__hash__-f.rst

    .. sip:method:: PyQt5.QtCore.QDate.isLeapYear
        :args:
            int
        :returns:
            bool
        :static:
        :description: QtCore/QDate-isLeapYear-f.rst

    .. sip:method:: PyQt5.QtCore.QDate.isNull
        :returns:
            bool
        :description: QtCore/QDate-isNull-f.rst

    .. sip:method:: PyQt5.QtCore.QDate.isValid
        :returns:
            bool
        :description: QtCore/QDate-isValid-f.rst

    .. sip:method:: PyQt5.QtCore.QDate.isValid
        :args:
            int
            int
            int
        :returns:
            bool
        :static:
        :description: QtCore/QDate-isValid-f-1.rst

    .. sip:method:: PyQt5.QtCore.QDate.__le__
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QDate`, datetime.date]
        :returns:
            bool
        :description: QtCore/QDate-__le__-f.rst

    .. sip:method:: PyQt5.QtCore.QDate.longDayName
        :args:
            int
            type: :sip:ref:`~PyQt5.QtCore.QDate.MonthNameType` = :sip:ref:`~PyQt5.QtCore.QDate.MonthNameType.DateFormat`
        :returns:
            str
        :static:
        :description: QtCore/QDate-longDayName-f.rst

    .. sip:method:: PyQt5.QtCore.QDate.longMonthName
        :args:
            int
            type: :sip:ref:`~PyQt5.QtCore.QDate.MonthNameType` = :sip:ref:`~PyQt5.QtCore.QDate.MonthNameType.DateFormat`
        :returns:
            str
        :static:
        :description: QtCore/QDate-longMonthName-f.rst

    .. sip:method:: PyQt5.QtCore.QDate.__lt__
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QDate`, datetime.date]
        :returns:
            bool
        :description: QtCore/QDate-__lt__-f.rst

    .. sip:method:: PyQt5.QtCore.QDate.month
        :returns:
            int
        :description: QtCore/QDate-month-f.rst

    .. sip:method:: PyQt5.QtCore.QDate.__ne__
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QDate`, datetime.date]
        :returns:
            bool
        :description: QtCore/QDate-__ne__-f.rst

    .. sip:method:: PyQt5.QtCore.QDate.__repr__
        :returns:
            str
        :description: QtCore/QDate-__repr__-f.rst

    .. sip:method:: PyQt5.QtCore.QDate.setDate
        :args:
            int
            int
            int
        :returns:
            bool
        :description: QtCore/QDate-setDate-f.rst

    .. sip:method:: PyQt5.QtCore.QDate.shortDayName
        :args:
            int
            type: :sip:ref:`~PyQt5.QtCore.QDate.MonthNameType` = :sip:ref:`~PyQt5.QtCore.QDate.MonthNameType.DateFormat`
        :returns:
            str
        :static:
        :description: QtCore/QDate-shortDayName-f.rst

    .. sip:method:: PyQt5.QtCore.QDate.shortMonthName
        :args:
            int
            type: :sip:ref:`~PyQt5.QtCore.QDate.MonthNameType` = :sip:ref:`~PyQt5.QtCore.QDate.MonthNameType.DateFormat`
        :returns:
            str
        :static:
        :description: QtCore/QDate-shortMonthName-f.rst

    .. sip:method:: PyQt5.QtCore.QDate.toJulianDay
        :returns:
            int
        :description: QtCore/QDate-toJulianDay-f.rst

    .. sip:method:: PyQt5.QtCore.QDate.toPyDate
        :returns:
            datetime.date
        :description: QtCore/QDate-toPyDate-f.rst

    .. sip:method:: PyQt5.QtCore.QDate.toString
        :args:
            format: :sip:ref:`~PyQt5.QtCore.Qt.DateFormat` = :sip:ref:`~PyQt5.QtCore.Qt.DateFormat.TextDate`
        :returns:
            str
        :description: QtCore/QDate-toString-f.rst

    .. sip:method:: PyQt5.QtCore.QDate.toString
        :args:
            str
        :returns:
            str
        :description: QtCore/QDate-toString-f-1.rst

    .. sip:method:: PyQt5.QtCore.QDate.weekNumber
        :returns:
            int
            int
        :description: QtCore/QDate-weekNumber-f.rst

    .. sip:method:: PyQt5.QtCore.QDate.year
        :returns:
            int
        :description: QtCore/QDate-year-f.rst
