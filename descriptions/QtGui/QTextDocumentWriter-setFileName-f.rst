.. sip:method-description::
    :status: todo
    :pysig: 341be97d9aff90c9978347f66f945b77
    :realsig: (const QString&)
    :digest: 30d2aa984edaef3ec908cb7de47fac90

Sets the name of the file to be written to *fileName*. Internally, :sip:ref:`~PyQt5.QtGui.QTextDocumentWriter` will create a :sip:ref:`~PyQt5.QtCore.QFile` and open it in :sip:ref:`~PyQt5.QtCore.QIODevice.OpenModeFlag.WriteOnly` mode, and use this file when writing the document.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QTextDocumentWriter.fileName`, :sip:ref:`~PyQt5.QtGui.QTextDocumentWriter.setDevice`.
