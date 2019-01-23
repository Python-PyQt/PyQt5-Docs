.. sip:method-description::
    :status: todo
    :pysig: 1308e54263e542b1f2686c8b968ef29a
    :realsig: (const QNetworkRequest&,QIODevice*)
    :digest: 42e839b4b698f2f41986860d94b3def7

Uploads the contents of *data* to the destination *request* and returns a new :sip:ref:`~PyQt5.QtNetwork.QNetworkReply` object that will be open for reply.

*data* must be opened for reading when this function is called and must remain valid until the :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager.finished` signal is emitted for this reply.

Whether anything will be available for reading from the returned object is protocol dependent. For HTTP, the server may send a small HTML page indicating the upload was successful (or not). Other protocols will probably have content in their replies.

**Note:** For HTTP, this request will send a PUT request, which most servers do not allow. Form upload mechanisms, including that of uploading files through HTML forms, use the POST mechanism.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager.get`, :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager.post`, :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager.deleteResource`, :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager.sendCustomRequest`.
