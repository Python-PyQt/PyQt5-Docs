.. sip:class-description::
    :status: todo
    :brief:  TODO
    :digest: eea51a348ece9116de62cf4b013257a2

The time zone offset data for a given moment in time, i.e. the time zone offsets and abbreviation to use at that moment in time.

* OffsetData::atUtc The datetime of the offset data in UTC time.

* OffsetData::offsetFromUtc The total offset from UTC in effect at the datetime.

* OffsetData::standardTimeOffset The standard time offset component of the total offset.

* OffsetData::daylightTimeOffset The DST offset component of the total offset.

* OffsetData::abbreviation The abbreviation in effect at the datetime.

For example, for time zone "Europe/Berlin" the OffsetDate in standard and DST might be:

* atUtc = :sip:ref:`~PyQt5.QtCore.QDateTime`\ (\ :sip:ref:`~PyQt5.QtCore.QDate`\ (2013, 1, 1), :sip:ref:`~PyQt5.QtCore.QTime`\ (0, 0, 0), :sip:ref:`~PyQt5.QtCore.Qt.TimeSpec.UTC`)

* offsetFromUtc = 3600

* standardTimeOffset = 3600

* daylightTimeOffset = 0

* abbreviation = "CET"

* atUtc = :sip:ref:`~PyQt5.QtCore.QDateTime`\ (\ :sip:ref:`~PyQt5.QtCore.QDate`\ (2013, 6, 1), :sip:ref:`~PyQt5.QtCore.QTime`\ (0, 0, 0), :sip:ref:`~PyQt5.QtCore.Qt.TimeSpec.UTC`)

* offsetFromUtc = 7200

* standardTimeOffset = 3600

* daylightTimeOffset = 3600

* abbreviation = "CEST"
