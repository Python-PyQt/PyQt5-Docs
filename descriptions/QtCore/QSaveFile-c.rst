.. sip:class-description::
    :status: todo
    :brief: Interface for safely writing to files
    :digest: 7b49bbc1b1c31e2bc3ba3c1729b1008d

The :sip:ref:`~PyQt5.QtCore.QSaveFile` class provides an interface for safely writing to files.

:sip:ref:`~PyQt5.QtCore.QSaveFile` is an I/O device for writing text and binary files, without losing existing data if the writing operation fails.

While writing, the contents will be written to a temporary file, and if no error happened, :sip:ref:`~PyQt5.QtCore.QSaveFile.commit` will move it to the final file. This ensures that no data at the final file is lost in case an error happens while writing, and no partially-written file is ever present at the final location. Always use :sip:ref:`~PyQt5.QtCore.QSaveFile` when saving entire documents to disk.

:sip:ref:`~PyQt5.QtCore.QSaveFile` automatically detects errors while writing, such as the full partition situation, where write() cannot write all the bytes. It will remember that an error happened, and will discard the temporary file in :sip:ref:`~PyQt5.QtCore.QSaveFile.commit`.

Much like with :sip:ref:`~PyQt5.QtCore.QFile`, the file is opened with :sip:ref:`~PyQt5.QtCore.QSaveFile.open`. Data is usually read and written using :sip:ref:`~PyQt5.QtCore.QDataStream` or :sip:ref:`~PyQt5.QtCore.QTextStream`, but you can also call the :sip:ref:`~PyQt5.QtCore.QIODevice`-inherited functions read(), readLine(), readAll(), write().

Unlike :sip:ref:`~PyQt5.QtCore.QFile`, calling  is not allowed. :sip:ref:`~PyQt5.QtCore.QSaveFile.commit` replaces it. If :sip:ref:`~PyQt5.QtCore.QSaveFile.commit` was not called and the :sip:ref:`~PyQt5.QtCore.QSaveFile` instance is destroyed, the temporary file is discarded.

To abort saving due to an application error, call :sip:ref:`~PyQt5.QtCore.QSaveFile.cancelWriting`, so that even a call to :sip:ref:`~PyQt5.QtCore.QSaveFile.commit` later on will not save.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QTextStream`, :sip:ref:`~PyQt5.QtCore.QDataStream`, :sip:ref:`~PyQt5.QtCore.QFileInfo`, :sip:ref:`~PyQt5.QtCore.QDir`, :sip:ref:`~PyQt5.QtCore.QFile`, :sip:ref:`~PyQt5.QtCore.QTemporaryFile`.
