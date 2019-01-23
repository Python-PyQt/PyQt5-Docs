.. sip:method-description::
    :status: todo
    :pysig: c43f8c6b670c417b3f4b38c80f004455
    :realsig: (QObject*)
    :digest: 21c736bf4c29b61c91fe1877d4d1f41e

Constructs a :sip:ref:`~PyQt5.QtCore.QTemporaryFile` (with the given *parent*) using as file template the application name returned by :sip:ref:`~PyQt5.QtCore.QCoreApplication.applicationName` (otherwise ``qt_temp``) followed by ".XXXXXX". The file is stored in the system's temporary directory, :sip:ref:`~PyQt5.QtCore.QDir.tempPath`.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QTemporaryFile.setFileTemplate`.
