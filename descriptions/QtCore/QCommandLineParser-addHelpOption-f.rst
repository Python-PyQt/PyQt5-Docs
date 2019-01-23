.. sip:method-description::
    :status: todo
    :pysig: 65d89dbfa1ca4bfdb4cbbcb8517ca43a
    :realsig: ()
    :digest: 007a55d1924d1dcb0f7dc4661ceffc22

Adds the help option (``-h``, ``--help`` and ``-?`` on Windows) This option is handled automatically by :sip:ref:`~PyQt5.QtCore.QCommandLineParser`.

Remember to use :sip:ref:`~PyQt5.QtCore.QCommandLineParser.setApplicationDescription` to set the application description, which will be displayed when this option is used.

Example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_tools_qcommandlineparser_main.py
    :lines: 56-95

Returns the option instance, which can be used to call :sip:ref:`~PyQt5.QtCore.QCommandLineParser.isSet`.
