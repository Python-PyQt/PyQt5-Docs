.. sip:class-description::
    :status: todo
    :brief: Allows the application to send network requests and receive replies
    :digest: 0e2c88b637b62d107b1ea471a9856f6a

The :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager` class allows the application to send network requests and receive replies.

The Network Access API is constructed around one :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager` object, which holds the common configuration and settings for the requests it sends. It contains the proxy and cache configuration, as well as the signals related to such issues, and reply signals that can be used to monitor the progress of a network operation. One :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager` instance should be enough for the whole Qt application. Since :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager` is based on :sip:ref:`~PyQt5.QtCore.QObject`, it can only be used from the thread it belongs to.

Once a :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager` object has been created, the application can use it to send requests over the network. A group of standard functions are supplied that take a request and optional data, and each return a :sip:ref:`~PyQt5.QtNetwork.QNetworkReply` object. The returned object is used to obtain any data returned in response to the corresponding request.

A simple download off the network could be accomplished with:

.. literalinclude:: ../../../snippets/qtbase-src-network-doc-snippets-code-src_network_access_qnetworkaccessmanager.py
    :lines: 54-58

:sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager` has an asynchronous API. When the ``replyFinished`` slot above is called, the parameter it takes is the :sip:ref:`~PyQt5.QtNetwork.QNetworkReply` object containing the downloaded data as well as meta-data (headers, etc.).

**Note:** After the request has finished, it is the responsibility of the user to delete the :sip:ref:`~PyQt5.QtNetwork.QNetworkReply` object at an appropriate time. Do not directly delete it inside the slot connected to :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager.finished`. You can use the deleteLater() function.

**Note:** :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager` queues the requests it receives. The number of requests executed in parallel is dependent on the protocol. Currently, for the HTTP protocol on desktop platforms, 6 requests are executed in parallel for one host/port combination.

A more involved example, assuming the manager is already existent, can be:

.. literalinclude:: ../../../snippets/qtbase-src-network-doc-snippets-code-src_network_access_qnetworkaccessmanager.py
    :lines: 63-72

.. _qnetworkaccessmanager-network-and-roaming-support:

Network and Roaming Support
---------------------------

With the addition of the `Bearer Management <https://doc.qt.io/qt-5/bearer-management.html>`_ API to Qt 4.7 :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager` gained the ability to manage network connections. :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager` can start the network interface if the device is offline and terminates the interface if the current process is the last one to use the uplink. Note that some platforms utilize grace periods from when the last application stops using a uplink until the system actually terminates the connectivity link. Roaming is equally transparent. Any queued/pending network requests are automatically transferred to the new access point.

Clients wanting to utilize this feature should not require any changes. In fact it is likely that existing platform specific connection code can simply be removed from the application.

**Note:** The network and roaming support in :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager` is conditional upon the platform supporting connection management. The :sip:ref:`~PyQt5.QtNetwork.QNetworkConfigurationManager.Capability.NetworkSessionRequired` can be used to detect whether :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager` utilizes this feature.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkRequest`, :sip:ref:`~PyQt5.QtNetwork.QNetworkReply`, :sip:ref:`~PyQt5.QtNetwork.QNetworkProxy`.
