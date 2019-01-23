.. sip:method-description::
    :status: todo
    :pysig: 4b99ff73a8a869319570237b5c57ab03
    :realsig: (const QString&,const QString&)
    :digest: 3a827c91d14f8ac3fb5756c502da72fb

This function declares a prefix *pre* in the current namespace context to be the namespace URI *uri*. The prefix remains in force until this context is popped, unless it is shadowed in a descendant context.

Note that there is an asymmetry in this library. :sip:ref:`~PyQt5.QtXml.QXmlNamespaceSupport.prefix` does not return the default "" prefix, even if you have declared one; to check for a default prefix, you must look it up explicitly using :sip:ref:`~PyQt5.QtXml.QXmlNamespaceSupport.uri`. This asymmetry exists to make it easier to look up prefixes for attribute names, where the default prefix is not allowed.

.. seealso:: :sip:ref:`~PyQt5.QtXml.QXmlNamespaceSupport.prefix`.
