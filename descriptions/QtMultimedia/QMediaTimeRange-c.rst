.. sip:class-description::
    :status: todo
    :brief: Represents a set of zero or more disjoint time intervals
    :digest: 1355aaafb897d4175ccf161e0ed11adf

The :sip:ref:`~PyQt5.QtMultimedia.QMediaTimeRange` class represents a set of zero or more disjoint time intervals.

The :sip:ref:`~PyQt5.QtMultimedia.QMediaTimeRange.earliestTime`, :sip:ref:`~PyQt5.QtMultimedia.QMediaTimeRange.latestTime`, :sip:ref:`~PyQt5.QtMultimedia.QMediaTimeRange.intervals` and :sip:ref:`~PyQt5.QtMultimedia.QMediaTimeRange.isEmpty` methods are used to get information about the current time range.

The :sip:ref:`~PyQt5.QtMultimedia.QMediaTimeRange.addInterval`, :sip:ref:`~PyQt5.QtMultimedia.QMediaTimeRange.removeInterval` and :sip:ref:`~PyQt5.QtMultimedia.QMediaTimeRange.clear` methods are used to modify the current time range.

When adding or removing intervals from the time range, existing intervals within the range may be expanded, trimmed, deleted, merged or split to ensure that all intervals within the time range remain distinct and disjoint. As a consequence, all intervals added or removed from a time range must be :sip:ref:`~PyQt5.QtMultimedia.QMediaTimeInterval.isNormal`.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QMediaTimeInterval`.
