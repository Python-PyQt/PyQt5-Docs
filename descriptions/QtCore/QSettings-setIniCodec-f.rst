.. sip:method-description::
    :status: todo
    :pysig: 46cd985fa7d56568c797b08fdc42071c
    :realsig: (QTextCodec*)
    :digest: 675e4d14ab2beccd1366232c7d607695

Sets the codec for accessing INI files (including ``.conf`` files on Unix) to *codec*. The codec is used for decoding any data that is read from the INI file, and for encoding any data that is written to the file. By default, no codec is used, and non-ASCII characters are encoded using standard INI escape sequences.

**Warning:** The codec must be set immediately after creating the :sip:ref:`~PyQt5.QtCore.QSettings` object, before accessing any data.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QSettings.iniCodec`.
