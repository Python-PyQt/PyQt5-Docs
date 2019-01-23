.. sip:method-description::
    :status: todo
    :pysig: 7a6323eaf1df50543fa0191762cb1b96
    :realsig: (QRadioTuner::SearchMode)
    :digest: 82c423425a4150be39748a634c54a78c

Search all stations in current band

Emits :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.stationFound`\ (int, QString) for every found station. After searching is completed, :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.searchingChanged`\ (bool) is emitted (false). If *searchMode* is set to :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.SearchMode.SearchGetStationId`, searching waits for station id (PI) on each frequency.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.searchForward`, :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.searchBackward`, `searching <https://doc.qt.io/qt-5/model-view-programming.html#searching>`_.
