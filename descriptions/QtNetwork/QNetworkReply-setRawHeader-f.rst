.. sip:method-description::
    :status: todo
    :pysig: 4430bbb68d4f82ee5c817d47e25daa8c
    :realsig: (const QByteArray&,const QByteArray&)
    :digest: ba2384aee7d5a3f61e1860f348e96a50

Sets the raw header *headerName* to be of value *value*. If *headerName* was previously set, it is overridden. Multiple HTTP headers of the same name are functionally equivalent to one single header with the values concatenated, separated by commas.

If *headerName* matches a known header, the value *value* will be parsed and the corresponding parsed form will also be set.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkReply.rawHeader`, :sip:ref:`~PyQt5.QtNetwork.QNetworkReply.header`, :sip:ref:`~PyQt5.QtNetwork.QNetworkReply.setHeader`, :sip:ref:`~PyQt5.QtNetwork.QNetworkRequest.setRawHeader`.
