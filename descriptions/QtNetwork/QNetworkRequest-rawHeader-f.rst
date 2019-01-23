.. sip:method-description::
    :status: todo
    :pysig: f3869674f8039d7f87e95384f34538a2
    :realsig: (const QByteArray&) const
    :digest: 3d547cd6962f286a22f67dfeb65e51de

Returns the raw form of header *headerName*. If no such header is present, an empty :sip:ref:`~PyQt5.QtCore.QByteArray` is returned, which may be indistinguishable from a header that is present but has no content (use :sip:ref:`~PyQt5.QtNetwork.QNetworkRequest.hasRawHeader` to find out if the header exists or not).

Raw headers can be set with :sip:ref:`~PyQt5.QtNetwork.QNetworkRequest.setRawHeader` or with :sip:ref:`~PyQt5.QtNetwork.QNetworkRequest.setHeader`.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkRequest.header`, :sip:ref:`~PyQt5.QtNetwork.QNetworkRequest.setRawHeader`.
