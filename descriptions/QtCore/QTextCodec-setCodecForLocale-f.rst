.. sip:method-description::
    :status: todo
    :pysig: cd02528b96e2954d58dc02e6307186cc
    :realsig: (QTextCodec*)
    :digest: cf99b86c89ddc0391688a254aaafb0a5

Set the codec to *c*; this will be returned by :sip:ref:`~PyQt5.QtCore.QTextCodec.codecForLocale`. If *c* is a null pointer, the codec is reset to the default.

This might be needed for some applications that want to use their own mechanism for setting the locale.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QTextCodec.codecForLocale`.
