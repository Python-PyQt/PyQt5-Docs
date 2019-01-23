.. sip:method-description::
    :status: todo
    :pysig: ca5d620f9be1458ae96cd8293f0aed27
    :realsig: (const QString&,QObject*)
    :digest: cf10155d60f186629a0efad29689745c

Constructs a :sip:ref:`~PyQt5.QtCore.QTemporaryFile` with a template filename of *templateName* and the specified *parent*. Upon opening the temporary file this will be used to create a unique filename.

If the *templateName* does not contain XXXXXX it will automatically be appended and used as the dynamic portion of the filename.

If *templateName* is a relative path, the path will be relative to the current working directory. You can use :sip:ref:`~PyQt5.QtCore.QDir.tempPath` to construct *templateName* if you want use the system's temporary directory.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QTemporaryFile.open`, :sip:ref:`~PyQt5.QtCore.QTemporaryFile.fileTemplate`.
