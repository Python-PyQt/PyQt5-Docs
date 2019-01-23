.. sip:enum-member-description::
    :status: todo
    :value: 0x000000e
    :digest: cc7c92b9d497e0c13ebc5fde7a0390ca

The configuration is currently used by an open network session (see :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.isOpen`). However this does not mean that the current process is the entity that created the open session. It merely indicates that if a new :sip:ref:`~PyQt5.QtNetwork.QNetworkSession` were to be constructed based on this configuration :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.state` would return :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.State.Connected`. This state implies the  state.
