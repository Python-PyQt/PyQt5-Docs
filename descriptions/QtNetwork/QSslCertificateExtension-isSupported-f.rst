.. sip:method-description::
    :status: todo
    :pysig: c506ff134babdd6e68ab3e6350e95305
    :realsig: () const
    :digest: 7ac8349366de58d35eadae381b4f5b82

Returns the true if this extension is supported. In this case, supported simply means that the structure of the :sip:ref:`~PyQt5.QtCore.QVariant` returned by the :sip:ref:`~PyQt5.QtNetwork.QSslCertificateExtension.value` accessor will remain unchanged between versions. Unsupported extensions can be freely used, however there is no guarantee that the returned data will have the same structure between versions.
