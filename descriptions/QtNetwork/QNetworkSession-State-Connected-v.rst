.. sip:enum-member-description::
    :status: todo
    :value: 3
    :digest: f00de49203d99a79b68181e12df364bb

The network session is connected. If the current process wishes to use this session it has to register its interest by calling :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.open`. A network session is considered to be ready for socket operations if it :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.isOpen` and connected.
