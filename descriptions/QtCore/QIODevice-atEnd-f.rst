.. sip:method-description::
    :status: todo
    :pysig: c506ff134babdd6e68ab3e6350e95305
    :realsig: () const
    :digest: 9c8ec58927b4f6182dfb9375365c0679

Returns ``true`` if the current read and write position is at the end of the device (i.e. there is no more data available for reading on the device); otherwise returns ``false``.

For some devices,  can return true even though there is more data to read. This special case only applies to devices that generate data in direct response to you calling :sip:ref:`~PyQt5.QtCore.QIODevice.read` (e.g., ``/dev`` or ``/proc`` files on Unix and `macOS <https://doc.qt.io/qt-5/qtwebengine-platform-notes.html#macos>`_, or console input / ``stdin`` on all platforms).

.. seealso:: :sip:ref:`~PyQt5.QtCore.QIODevice.bytesAvailable`, :sip:ref:`~PyQt5.QtCore.QIODevice.read`, :sip:ref:`~PyQt5.QtCore.QIODevice.isSequential`.
