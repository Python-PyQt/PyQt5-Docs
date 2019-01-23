.. sip:method-description::
    :status: todo
    :pysig: 65d89dbfa1ca4bfdb4cbbcb8517ca43a
    :realsig: ()
    :digest: a404f59dc690601889bc68070bd9bf98

Adds the ``-v`` / ``--version`` option, which displays the version string of the application.

This option is handled automatically by :sip:ref:`~PyQt5.QtCore.QCommandLineParser`.

You can set the actual version string by using :sip:ref:`~PyQt5.QtCore.QCoreApplication.setApplicationVersion`.

Returns the option instance, which can be used to call :sip:ref:`~PyQt5.QtCore.QCommandLineParser.isSet`.
