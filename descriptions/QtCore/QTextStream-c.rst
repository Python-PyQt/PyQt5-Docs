.. sip:class-description::
    :status: todo
    :brief: Convenient interface for reading and writing text
    :digest: aa1a7618ea4964f4c1ff0433c6cd22eb

The :sip:ref:`~PyQt5.QtCore.QTextStream` class provides a convenient interface for reading and writing text.

:sip:ref:`~PyQt5.QtCore.QTextStream` can operate on a :sip:ref:`~PyQt5.QtCore.QIODevice`, a :sip:ref:`~PyQt5.QtCore.QByteArray` or a QString. Using :sip:ref:`~PyQt5.QtCore.QTextStream`'s streaming operators, you can conveniently read and write words, lines and numbers. For generating text, :sip:ref:`~PyQt5.QtCore.QTextStream` supports formatting options for field padding and alignment, and formatting of numbers. Example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_io_qtextstream.py
    :lines: 54-59

It's also common to use :sip:ref:`~PyQt5.QtCore.QTextStream` to read console input and write console output. :sip:ref:`~PyQt5.QtCore.QTextStream` is locale aware, and will automatically decode standard input using the correct codec. Example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_io_qtextstream.py
    :lines: 64-68

Besides using :sip:ref:`~PyQt5.QtCore.QTextStream`'s constructors, you can also set the device or string :sip:ref:`~PyQt5.QtCore.QTextStream` operates on by calling :sip:ref:`~PyQt5.QtCore.QTextStream.setDevice` or setString(). You can seek to a position by calling :sip:ref:`~PyQt5.QtCore.QTextStream.seek`, and :sip:ref:`~PyQt5.QtCore.QTextStream.atEnd` will return true when there is no data left to be read. If you call :sip:ref:`~PyQt5.QtCore.flush`, :sip:ref:`~PyQt5.QtCore.QTextStream` will empty all data from its write buffer into the device and call :sip:ref:`~PyQt5.QtCore.flush` on the device.

Internally, :sip:ref:`~PyQt5.QtCore.QTextStream` uses a Unicode based buffer, and :sip:ref:`~PyQt5.QtCore.QTextCodec` is used by :sip:ref:`~PyQt5.QtCore.QTextStream` to automatically support different character sets. By default, :sip:ref:`~PyQt5.QtCore.QTextCodec.codecForLocale` is used for reading and writing, but you can also set the codec by calling :sip:ref:`~PyQt5.QtCore.QTextStream.setCodec`. Automatic Unicode detection is also supported. When this feature is enabled (the default behavior), :sip:ref:`~PyQt5.QtCore.QTextStream` will detect the UTF-16 or the UTF-32 BOM (Byte Order Mark) and switch to the appropriate UTF codec when reading. :sip:ref:`~PyQt5.QtCore.QTextStream` does not write a BOM by default, but you can enable this by calling :sip:ref:`~PyQt5.QtCore.QTextStream.setGenerateByteOrderMark`\ (true). When :sip:ref:`~PyQt5.QtCore.QTextStream` operates on a QString directly, the codec is disabled.

There are three general ways to use :sip:ref:`~PyQt5.QtCore.QTextStream` when reading text files:

* Chunk by chunk, by calling :sip:ref:`~PyQt5.QtCore.QTextStream.readLine` or :sip:ref:`~PyQt5.QtCore.QTextStream.readAll`.

* Word by word. :sip:ref:`~PyQt5.QtCore.QTextStream` supports streaming into QStrings, :sip:ref:`~PyQt5.QtCore.QByteArray`\ s and char\* buffers. Words are delimited by space, and leading white space is automatically skipped.

* Character by character, by streaming into QChar or char types. This method is often used for convenient input handling when parsing files, independent of character encoding and end-of-line semantics. To skip white space, call :sip:ref:`~PyQt5.QtCore.QTextStream.skipWhiteSpace`.

Since the text stream uses a buffer, you should not read from the stream using the implementation of a superclass. For instance, if you have a :sip:ref:`~PyQt5.QtCore.QFile` and read from it directly using QFile::readLine() instead of using the stream, the text stream's internal position will be out of sync with the file's position.

By default, when reading numbers from a stream of text, :sip:ref:`~PyQt5.QtCore.QTextStream` will automatically detect the number's base representation. For example, if the number starts with "0x", it is assumed to be in hexadecimal form. If it starts with the digits 1-9, it is assumed to be in decimal form, and so on. You can set the integer base, thereby disabling the automatic detection, by calling :sip:ref:`~PyQt5.QtCore.QTextStream.setIntegerBase`. Example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_io_qtextstream.py
    :lines: 73-80

:sip:ref:`~PyQt5.QtCore.QTextStream` supports many formatting options for generating text. You can set the field width and pad character by calling :sip:ref:`~PyQt5.QtCore.QTextStream.setFieldWidth` and :sip:ref:`~PyQt5.QtCore.QTextStream.setPadChar`. Use :sip:ref:`~PyQt5.QtCore.QTextStream.setFieldAlignment` to set the alignment within each field. For real numbers, call :sip:ref:`~PyQt5.QtCore.QTextStream.setRealNumberNotation` and :sip:ref:`~PyQt5.QtCore.QTextStream.setRealNumberPrecision` to set the notation (\ :sip:ref:`~PyQt5.QtCore.QTextStream.RealNumberNotation.SmartNotation`, :sip:ref:`~PyQt5.QtCore.QTextStream.RealNumberNotation.ScientificNotation`, :sip:ref:`~PyQt5.QtCore.QTextStream.RealNumberNotation.FixedNotation`) and precision in digits of the generated number. Some extra number formatting options are also available through :sip:ref:`~PyQt5.QtCore.QTextStream.setNumberFlags`.

.. _qtextstream-qtextstream-manipulators:

Like ``<iostream>`` in the standard C++ library, :sip:ref:`~PyQt5.QtCore.QTextStream` also defines several global manipulator functions:

+---------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Manipulator         | Description                                                                                                                                                                             |
+=====================+=========================================================================================================================================================================================+
| ``bin``             | Same as :sip:ref:`~PyQt5.QtCore.QTextStream.setIntegerBase`\ (2).                                                                                                                       |
+---------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| ``oct``             | Same as :sip:ref:`~PyQt5.QtCore.QTextStream.setIntegerBase`\ (8).                                                                                                                       |
+---------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| ``dec``             | Same as :sip:ref:`~PyQt5.QtCore.QTextStream.setIntegerBase`\ (10).                                                                                                                      |
+---------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| ``hex``             | Same as :sip:ref:`~PyQt5.QtCore.QTextStream.setIntegerBase`\ (16).                                                                                                                      |
+---------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| ``showbase``        | Same as :sip:ref:`~PyQt5.QtCore.QTextStream.setNumberFlags`\ (\ :sip:ref:`~PyQt5.QtCore.QTextStream.numberFlags` | :sip:ref:`~PyQt5.QtCore.QTextStream.NumberFlag.ShowBase`).           |
+---------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| ``forcesign``       | Same as :sip:ref:`~PyQt5.QtCore.QTextStream.setNumberFlags`\ (\ :sip:ref:`~PyQt5.QtCore.QTextStream.numberFlags` | :sip:ref:`~PyQt5.QtCore.QTextStream.NumberFlag.ForceSign`).          |
+---------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| ``forcepoint``      | Same as :sip:ref:`~PyQt5.QtCore.QTextStream.setNumberFlags`\ (\ :sip:ref:`~PyQt5.QtCore.QTextStream.numberFlags` | :sip:ref:`~PyQt5.QtCore.QTextStream.NumberFlag.ForcePoint`).         |
+---------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| ``noshowbase``      | Same as :sip:ref:`~PyQt5.QtCore.QTextStream.setNumberFlags`\ (\ :sip:ref:`~PyQt5.QtCore.QTextStream.numberFlags` & ~\ :sip:ref:`~PyQt5.QtCore.QTextStream.NumberFlag.ShowBase`).        |
+---------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| ``noforcesign``     | Same as :sip:ref:`~PyQt5.QtCore.QTextStream.setNumberFlags`\ (\ :sip:ref:`~PyQt5.QtCore.QTextStream.numberFlags` & ~\ :sip:ref:`~PyQt5.QtCore.QTextStream.NumberFlag.ForceSign`).       |
+---------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| ``noforcepoint``    | Same as :sip:ref:`~PyQt5.QtCore.QTextStream.setNumberFlags`\ (\ :sip:ref:`~PyQt5.QtCore.QTextStream.numberFlags` & ~\ :sip:ref:`~PyQt5.QtCore.QTextStream.NumberFlag.ForcePoint`).      |
+---------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| ``uppercasebase``   | Same as :sip:ref:`~PyQt5.QtCore.QTextStream.setNumberFlags`\ (\ :sip:ref:`~PyQt5.QtCore.QTextStream.numberFlags` | :sip:ref:`~PyQt5.QtCore.QTextStream.NumberFlag.UppercaseBase`).      |
+---------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| ``uppercasedigits`` | Same as :sip:ref:`~PyQt5.QtCore.QTextStream.setNumberFlags`\ (\ :sip:ref:`~PyQt5.QtCore.QTextStream.numberFlags` | :sip:ref:`~PyQt5.QtCore.QTextStream.NumberFlag.UppercaseDigits`).    |
+---------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| ``lowercasebase``   | Same as :sip:ref:`~PyQt5.QtCore.QTextStream.setNumberFlags`\ (\ :sip:ref:`~PyQt5.QtCore.QTextStream.numberFlags` & ~\ :sip:ref:`~PyQt5.QtCore.QTextStream.NumberFlag.UppercaseBase`).   |
+---------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| ``lowercasedigits`` | Same as :sip:ref:`~PyQt5.QtCore.QTextStream.setNumberFlags`\ (\ :sip:ref:`~PyQt5.QtCore.QTextStream.numberFlags` & ~\ :sip:ref:`~PyQt5.QtCore.QTextStream.NumberFlag.UppercaseDigits`). |
+---------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| ``fixed``           | Same as :sip:ref:`~PyQt5.QtCore.QTextStream.setRealNumberNotation`\ (\ :sip:ref:`~PyQt5.QtCore.QTextStream.RealNumberNotation.FixedNotation`).                                          |
+---------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| ``scientific``      | Same as :sip:ref:`~PyQt5.QtCore.QTextStream.setRealNumberNotation`\ (\ :sip:ref:`~PyQt5.QtCore.QTextStream.RealNumberNotation.ScientificNotation`).                                     |
+---------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| ``left``            | Same as :sip:ref:`~PyQt5.QtCore.QTextStream.setFieldAlignment`\ (\ :sip:ref:`~PyQt5.QtCore.QTextStream.FieldAlignment.AlignLeft`).                                                      |
+---------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| ``right``           | Same as :sip:ref:`~PyQt5.QtCore.QTextStream.setFieldAlignment`\ (\ :sip:ref:`~PyQt5.QtCore.QTextStream.FieldAlignment.AlignRight`).                                                     |
+---------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| ``center``          | Same as :sip:ref:`~PyQt5.QtCore.QTextStream.setFieldAlignment`\ (\ :sip:ref:`~PyQt5.QtCore.QTextStream.FieldAlignment.AlignCenter`).                                                    |
+---------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| ``endl``            | Same as operator<<('\\n') and :sip:ref:`~PyQt5.QtCore.flush`.                                                                                                                           |
+---------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| ``flush``           | Same as :sip:ref:`~PyQt5.QtCore.flush`.                                                                                                                                                 |
+---------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| ``reset``           | Same as :sip:ref:`~PyQt5.QtCore.reset`.                                                                                                                                                 |
+---------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| ``ws``              | Same as :sip:ref:`~PyQt5.QtCore.QTextStream.skipWhiteSpace`.                                                                                                                            |
+---------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| ``bom``             | Same as :sip:ref:`~PyQt5.QtCore.QTextStream.setGenerateByteOrderMark`\ (true).                                                                                                          |
+---------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

In addition, Qt provides three global manipulators that take a parameter: :sip:ref:`~PyQt5.QtCore.qSetFieldWidth`, qSetPadChar(), and :sip:ref:`~PyQt5.QtCore.qSetRealNumberPrecision`.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QDataStream`, :sip:ref:`~PyQt5.QtCore.QIODevice`, :sip:ref:`~PyQt5.QtCore.QFile`, :sip:ref:`~PyQt5.QtCore.QBuffer`, :sip:ref:`~PyQt5.QtNetwork.QTcpSocket`, `Text Codecs Example <https://doc.qt.io/qt-5/qtwidgets-tools-codecs-example.html>`_.
