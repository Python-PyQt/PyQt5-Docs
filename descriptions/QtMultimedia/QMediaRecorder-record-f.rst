.. sip:method-description::
    :status: todo
    :pysig: d41d8cd98f00b204e9800998ecf8427e
    :realsig: ()
    :digest: 8bc6dee244120b0a5d5490d25d70b6aa

Start recording.

While the recorder state is changed immediately to :sip:ref:`~PyQt5.QtMultimedia.QMediaRecorder.State.RecordingState`, recording may start asynchronously, with :sip:ref:`~PyQt5.QtMultimedia.QMediaRecorder.statusChanged`\ (\ :sip:ref:`~PyQt5.QtMultimedia.QMediaRecorder.Status.RecordingStatus`) signal emitted when recording starts.

If recording fails :sip:ref:`~PyQt5.QtMultimedia.QMediaRecorder.error` signal is emitted with recorder state being reset back to :sip:ref:`~PyQt5.QtMultimedia.QMediaRecorder.State.StoppedState`.
