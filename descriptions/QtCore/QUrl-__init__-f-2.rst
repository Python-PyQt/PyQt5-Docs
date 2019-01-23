.. sip:method-description::
    :status: todo
    :pysig: 4dc982fc872f4a54c03db2025bedf064
    :realsig: (const QString&,QUrl::ParsingMode)
    :digest: 773c072559242646c53bef145f4a3814

Constructs a URL by parsing *url*. :sip:ref:`~PyQt5.QtCore.QUrl` will automatically percent encode all characters that are not allowed in a URL and decode the percent-encoded sequences that represent an unreserved character (letters, digits, hyphens, undercores, dots and tildes). All other characters are left in their original forms.

Parses the *url* using the parser mode *parsingMode*. In :sip:ref:`~PyQt5.QtCore.QUrl.ParsingMode.TolerantMode` (the default), :sip:ref:`~PyQt5.QtCore.QUrl` will correct certain mistakes, notably the presence of a percent character ('%') not followed by two hexadecimal digits, and it will accept any character in any position. In :sip:ref:`~PyQt5.QtCore.QUrl.ParsingMode.StrictMode`, encoding mistakes will not be tolerated and :sip:ref:`~PyQt5.QtCore.QUrl` will also check that certain forbidden characters are not present in unencoded form. If an error is detected in :sip:ref:`~PyQt5.QtCore.QUrl.ParsingMode.StrictMode`, :sip:ref:`~PyQt5.QtCore.QUrl.isValid` will return false. The parsing mode :sip:ref:`~PyQt5.QtCore.QUrl.ParsingMode.DecodedMode` is not permitted in this context.

Example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_io_qurl.py
    :lines: 54-55

To construct a URL from an encoded string, you can also use :sip:ref:`~PyQt5.QtCore.QUrl.fromEncoded`:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_io_qurl.py
    :lines: 60-60

Both functions are equivalent and, in Qt 5, both functions accept encoded data. Usually, the choice of the :sip:ref:`~PyQt5.QtCore.QUrl` constructor or setUrl() versus :sip:ref:`~PyQt5.QtCore.QUrl.fromEncoded` will depend on the source data: the constructor and setUrl() take a QString, whereas :sip:ref:`~PyQt5.QtCore.QUrl.fromEncoded` takes a :sip:ref:`~PyQt5.QtCore.QByteArray`.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QUrl.fromEncoded`, :sip:ref:`~PyQt5.QtCore.QUrl.ParsingMode.TolerantMode`, :sip:ref:`~PyQt5.QtCore.QUrl.setUrl`.
