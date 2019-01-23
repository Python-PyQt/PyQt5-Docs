.. sip:method-description::
    :status: todo
    :pysig: 38a46868523b8b5698cc3d5b900e1590
    :realsig: (QNetworkRequest::KnownHeaders) const
    :digest: f20a3766b2b6860db6580a49e3c637e9

Returns the value of the known header *header*, if that header was sent by the remote server. If the header was not sent, returns an invalid :sip:ref:`~PyQt5.QtCore.QVariant`.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkReply.rawHeader`, :sip:ref:`~PyQt5.QtNetwork.QNetworkReply.setHeader`, :sip:ref:`~PyQt5.QtNetwork.QNetworkRequest.header`.
