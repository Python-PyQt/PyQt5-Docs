.. sip:class-description::
    :status: todo
    :brief: Control over the system's access points and enables session management for cases when multiple clients access the same access point
    :digest: 20db17dca26464d8cb755e28eb2cf2f1

The :sip:ref:`~PyQt5.QtNetwork.QNetworkSession` class provides control over the system's access points and enables session management for cases when multiple clients access the same access point.

A :sip:ref:`~PyQt5.QtNetwork.QNetworkSession` enables control over the system's network interfaces. The session's configuration parameter are determined via the :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration` object to which it is bound. Depending on the type of the session (single access point or service network) a session may be linked to one or more network interfaces. By means of :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.open` and :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.close` of network sessions a developer can start and stop the systems network interfaces. If the configuration represents multiple access points (see :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.Type.ServiceNetwork`) more advanced features such as roaming may be supported.

:sip:ref:`~PyQt5.QtNetwork.QNetworkSession` supports session management within the same process and depending on the platform's capabilities may support out-of-process sessions. If the same network configuration is used by multiple open sessions the underlying network interface is only terminated once the last session has been closed.

.. _qnetworksession-roaming:

Roaming
-------

Applications may connect to the :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.preferredConfigurationChanged` signal in order to receive notifications when a more suitable access point becomes available. In response to this signal the application must either initiate the roaming via :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.migrate` or :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.ignore` the new access point. Once the session has roamed the :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.newConfigurationActivated` signal is emitted. The application may now test the carrier and must either :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.accept` or :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.reject` it. The session will return to the previous access point if the roaming was rejected. The subsequent state diagram depicts the required state transitions.

.. image:: ../../../images/roaming-states.png

Some platforms may distinguish forced roaming and application level roaming (ALR). ALR implies that the application controls (via :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.migrate`, :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.ignore`, :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.accept` and :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.reject`) whether a network session can roam from one access point to the next. Such control is useful if the application maintains stateful socket connections and wants to control the transition from one interface to the next. Forced roaming implies that the system automatically roams to the next network without consulting the application. This has the advantage that the application can make use of roaming features without actually being aware of it. It is expected that the application detects that the underlying socket is broken and automatically reconnects via the new network link.

If the platform supports both modes of roaming, an application indicates its preference by connecting to the :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.preferredConfigurationChanged` signal. Connecting to this signal means that the application wants to take control over the roaming behavior and therefore implies application level roaming. If the client does not connect to the :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.preferredConfigurationChanged`, forced roaming is used. If forced roaming is not supported the network session will not roam by default.

Some applications may want to suppress any form of roaming altogether. Possible use cases may be high priority downloads or remote services which cannot handle a roaming enabled client. Clients can suppress roaming by connecting to the :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.preferredConfigurationChanged` signal and answer each signal emission with :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.ignore`.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration`, :sip:ref:`~PyQt5.QtNetwork.QNetworkConfigurationManager`.
