.. sip:method-description::
    :status: todo
    :pysig: d4aa9c72e3ce19d031d88fdbf681f5d9
    :realsig: (int,const QUrl&)
    :digest: 4fd207d6e5e5aa272343ae11a01518f5

Loads data of the specified *type* from the resource with the given *name*.

This function is called by the rich text engine to request data that isn't directly stored by :sip:ref:`~PyQt5.QtGui.QTextDocument`, but still associated with it. For example, images are referenced indirectly by the name attribute of a :sip:ref:`~PyQt5.QtGui.QTextImageFormat` object.

When called by Qt, *type* is one of the values of :sip:ref:`~PyQt5.QtGui.QTextDocument.ResourceType`.

If the :sip:ref:`~PyQt5.QtGui.QTextDocument` is a child object of a :sip:ref:`~PyQt5.QtCore.QObject` that has an invokable  method such as QTextEdit, QTextBrowser or a :sip:ref:`~PyQt5.QtGui.QTextDocument` itself then the default implementation tries to retrieve the data from the parent.
