.. sip:method-description::
    :status: todo
    :pysig: b83170c533e4d550016c58f38a9f2cd1
    :realsig: () const
    :digest: 81eb494c1f6f63af1cae5dd78bdc82f8

Returns a status code indicating the first error that was met by :sip:ref:`~PyQt5.QtCore.QSettings`, or :sip:ref:`~PyQt5.QtCore.QSettings.Status.NoError` if no error occurred.

Be aware that :sip:ref:`~PyQt5.QtCore.QSettings` delays performing some operations. For this reason, you might want to call :sip:ref:`~PyQt5.QtCore.QSettings.sync` to ensure that the data stored in :sip:ref:`~PyQt5.QtCore.QSettings` is written to disk before calling .

.. seealso:: :sip:ref:`~PyQt5.QtCore.QSettings.sync`.
