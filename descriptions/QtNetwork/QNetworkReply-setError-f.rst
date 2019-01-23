.. sip:method-description::
    :status: todo
    :pysig: 4a7d1bffaba322caa0ef89b52b5b3cc4
    :realsig: (QNetworkReply::NetworkError,const QString&)
    :digest: 0a53dd186d82aec299bd13218f6c937b

Sets the error condition to be *errorCode*. The human-readable message is set with *errorString*.

Calling  does not emit the error(\ :sip:ref:`~PyQt5.QtNetwork.QNetworkReply.NetworkError`) signal.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkReply.error`, errorString().
