.. sip:method-description::
    :status: todo
    :pysig: d4aa9c72e3ce19d031d88fdbf681f5d9
    :realsig: (int,const QUrl&) const
    :digest: 4b9d8de04f6b4f1451b00c1eff5853ea

Returns data of the specified *type* from the resource with the given *name*.

This function is called by the rich text engine to request data that isn't directly stored by :sip:ref:`~PyQt5.QtGui.QTextDocument`, but still associated with it. For example, images are referenced indirectly by the name attribute of a :sip:ref:`~PyQt5.QtGui.QTextImageFormat` object.

Resources are cached internally in the document. If a resource can not be found in the cache, :sip:ref:`~PyQt5.QtGui.QTextDocument.loadResource` is called to try to load the resource. :sip:ref:`~PyQt5.QtGui.QTextDocument.loadResource` should then use :sip:ref:`~PyQt5.QtGui.QTextDocument.addResource` to add the resource to the cache.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QTextDocument.ResourceType`.
