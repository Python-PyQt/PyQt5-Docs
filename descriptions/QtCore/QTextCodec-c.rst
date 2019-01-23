.. sip:class-description::
    :status: todo
    :brief: Conversions between text encodings
    :digest: 65fd24ee5e4a4ef44193ddca5ac46711

The :sip:ref:`~PyQt5.QtCore.QTextCodec` class provides conversions between text encodings.

Qt uses Unicode to store, draw and manipulate strings. In many situations you may wish to deal with data that uses a different encoding. For example, most Japanese documents are still stored in Shift-JIS or ISO 2022-JP, while Russian users often have their documents in KOI8-R or Windows-1251.

Qt provides a set of :sip:ref:`~PyQt5.QtCore.QTextCodec` classes to help with converting non-Unicode formats to and from Unicode. You can also create your own codec classes.

The supported encodings are:

* `Big5 <https://doc.qt.io/qt-5/codec-big5.html>`_

* `Big5-HKSCS <https://doc.qt.io/qt-5/codec-big5hkscs.html>`_

* CP949

* `EUC-JP <https://doc.qt.io/qt-5/codec-eucjp.html>`_

* `EUC-KR <https://doc.qt.io/qt-5/codec-euckr.html>`_

* `GB18030 <https://doc.qt.io/qt-5/codec-gbk.html>`_

* HP-ROMAN8

* IBM 850

* IBM 866

* IBM 874

* `ISO 2022-JP <https://doc.qt.io/qt-5/codecs-jis.html>`_

* ISO 8859-1 to 10

* ISO 8859-13 to 16

* Iscii-Bng, Dev, Gjr, Knd, Mlm, Ori, Pnj, Tlg, and Tml

* KOI8-R

* KOI8-U

* Macintosh

* `Shift-JIS <https://doc.qt.io/qt-5/codec-sjis.html>`_

* TIS-620

* `TSCII <https://doc.qt.io/qt-5/codec-tscii.html>`_

* UTF-8

* UTF-16

* UTF-16BE

* UTF-16LE

* UTF-32

* UTF-32BE

* UTF-32LE

* Windows-1250 to 1258

If Qt is compiled with ICU support enabled, most codecs supported by ICU will also be available to the application.

:sip:ref:`~PyQt5.QtCore.QTextCodec`\ s can be used as follows to convert some locally encoded string to Unicode. Suppose you have some string encoded in Russian KOI8-R encoding, and want to convert it to Unicode. The simple way to do it is like this:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_codecs_qtextcodec.py
    :lines: 54-56

After this, ``string`` holds the text converted to Unicode. Converting a string from Unicode to the local encoding is just as easy:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_codecs_qtextcodec.py
    :lines: 61-63

To read or write files in various encodings, use :sip:ref:`~PyQt5.QtCore.QTextStream` and its :sip:ref:`~PyQt5.QtCore.QTextStream.setCodec` function. See the `Codecs <https://doc.qt.io/qt-5/qtwidgets-tools-codecs-example.html>`_ example for an application of :sip:ref:`~PyQt5.QtCore.QTextCodec` to file I/O.

Some care must be taken when trying to convert the data in chunks, for example, when receiving it over a network. In such cases it is possible that a multi-byte character will be split over two chunks. At best this might result in the loss of a character and at worst cause the entire conversion to fail.

The approach to use in these situations is to create a :sip:ref:`~PyQt5.QtCore.QTextDecoder` object for the codec and use this :sip:ref:`~PyQt5.QtCore.QTextDecoder` for the whole decoding process, as shown below:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_codecs_qtextcodec.py
    :lines: 68-76

The :sip:ref:`~PyQt5.QtCore.QTextDecoder` object maintains state between chunks and therefore works correctly even if a multi-byte character is split between chunks.

.. _qtextcodec-creating-your-own-codec-class:

Creating Your Own Codec Class
-----------------------------

Support for new text encodings can be added to Qt by creating :sip:ref:`~PyQt5.QtCore.QTextCodec` subclasses.

The pure virtual functions describe the encoder to the system and the coder is used as required in the different text file formats supported by :sip:ref:`~PyQt5.QtCore.QTextStream`, and under X11, for the locale-specific character input and output.

To add support for another encoding to Qt, make a subclass of :sip:ref:`~PyQt5.QtCore.QTextCodec` and implement the functions listed in the table below.

+------------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Function                                             | Description                                                                                                                                                                                                                                                                |
+======================================================+============================================================================================================================================================================================================================================================================+
| :sip:ref:`~PyQt5.QtCore.QTextCodec.name`             | Returns the official name for the encoding. If the encoding is listed in the `IANA character-sets encoding file <https://doc.qt.io/qt-5/http://www.iana.org/assignments/character-sets/character-sets.xml>`_, the name should be the preferred MIME name for the encoding. |
+------------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :sip:ref:`~PyQt5.QtCore.QTextCodec.aliases`          | Returns a list of alternative names for the encoding. :sip:ref:`~PyQt5.QtCore.QTextCodec` provides a default implementation that returns an empty list. For example, "ISO-8859-1" has "latin1", "CP819", "IBM819", and "iso-ir-100" as aliases.                            |
+------------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :sip:ref:`~PyQt5.QtCore.QTextCodec.mibEnum`          | Return the MIB enum for the encoding if it is listed in the `IANA character-sets encoding file <https://doc.qt.io/qt-5/http://www.iana.org/assignments/character-sets/character-sets.xml>`_.                                                                               |
+------------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :sip:ref:`~PyQt5.QtCore.QTextCodec.convertToUnicode` | Converts an 8-bit character string to Unicode.                                                                                                                                                                                                                             |
+------------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| convertFromUnicode()                                 | Converts a Unicode string to an 8-bit character string.                                                                                                                                                                                                                    |
+------------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

.. seealso:: :sip:ref:`~PyQt5.QtCore.QTextStream`, :sip:ref:`~PyQt5.QtCore.QTextDecoder`, :sip:ref:`~PyQt5.QtCore.QTextEncoder`, `Text Codecs Example <https://doc.qt.io/qt-5/qtwidgets-tools-codecs-example.html>`_.
