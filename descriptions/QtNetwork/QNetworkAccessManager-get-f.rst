.. sip:method-description::
    :status: todo
    :pysig: 90168ed5a9433351a4e7f57db9af85b5
    :realsig: (const QNetworkRequest&)
    :digest: ac664299a6e98eea9a5592459eed008a

Posts a request to obtain the contents of the target *request* and returns a new :sip:ref:`~PyQt5.QtNetwork.QNetworkReply` object opened for reading which emits the :sip:ref:`~PyQt5.QtCore.QIODevice.readyRead` signal whenever new data arrives.

The contents as well as associated headers will be downloaded.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager.post`, :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager.put`, :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager.deleteResource`, :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager.sendCustomRequest`.
