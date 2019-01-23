.. sip:method-description::
    :status: todo
    :pysig: 9cb377390baeab766a645b3b1b5bf5ad
    :realsig: (const QString&,QSsl::EncodingFormat,QRegExp::PatternSyntax)
    :digest: ce0f3668d8120d51a1bfbd15428b4c1a

Searches all files in the *path* for certificates encoded in the specified *format* and returns them in a list. *path* must be a file or a pattern matching one or more files, as specified by *syntax*.

Example:

.. literalinclude:: ../../../snippets/qtbase-src-network-doc-snippets-code-src_network_ssl_qsslcertificate.py
    :lines: 54-58

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QSslCertificate.fromData`.
