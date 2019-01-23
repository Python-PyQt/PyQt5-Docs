.. sip:class-description::
    :status: todo
    :brief: Represents a time interval with integer precision
    :digest: eda17774344548a2d9b9b0656a4f0924

The :sip:ref:`~PyQt5.QtMultimedia.QMediaTimeInterval` class represents a time interval with integer precision.

An interval is specified by an inclusive :sip:ref:`~PyQt5.QtMultimedia.QMediaTimeInterval.start` and :sip:ref:`~PyQt5.QtMultimedia.QMediaTimeInterval.end` time. These must be set in the constructor, as this is an immutable class. The specific units of time represented by the class have not been defined - it is suitable for any times which can be represented by a signed 64 bit integer.

The :sip:ref:`~PyQt5.QtMultimedia.QMediaTimeInterval.isNormal` method determines if a time interval is normal (a normal time interval has :sip:ref:`~PyQt5.QtMultimedia.QMediaTimeInterval.start` <= :sip:ref:`~PyQt5.QtMultimedia.QMediaTimeInterval.end`). A normal interval can be received from an abnormal interval by calling the :sip:ref:`~PyQt5.QtMultimedia.QMediaTimeInterval.normalized` method.

The :sip:ref:`~PyQt5.QtMultimedia.QMediaTimeInterval.contains` method determines if a specified time lies within the time interval.

The :sip:ref:`~PyQt5.QtMultimedia.QMediaTimeInterval.translated` method returns a time interval which has been translated forwards or backwards through time by a specified offset.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QMediaTimeRange`.
