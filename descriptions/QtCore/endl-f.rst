.. sip:method-description::
    :status: todo
    :pysig: dc262aeb30275d5909112b15166cac97
    :realsig: (QTextStream&)
    :digest: 258d4b40d5c4c2f18f87fc990a00f250

Writes '\\n' to the *stream* and flushes the stream.

Equivalent to

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_io_qtextstream.py
    :lines: 134-134

Note: On Windows, all '\\n' characters are written as '\\r\\n' if :sip:ref:`~PyQt5.QtCore.QTextStream`'s device or string is opened using the :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag.Text` flag.

.. seealso:: :sip:ref:`~PyQt5.QtCore.flush`, :sip:ref:`~PyQt5.QtCore.reset`, :ref:`QTextStream manipulators<qtextstream-qtextstream-manipulators>`.
