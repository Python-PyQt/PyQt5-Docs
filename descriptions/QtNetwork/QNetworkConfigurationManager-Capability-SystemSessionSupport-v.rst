.. sip:enum-member-description::
    :status: todo
    :value: 0x00000004
    :digest: ba17635285daa650c86ff1664fb66c0a

If this flag is set the underlying platform ensures that a network interface is not shut down until the last network session has been :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.close`. This works across multiple processes. If the platform session support is missing this API can only ensure the above behavior for network sessions within the same process. In general mobile platforms have such support whereas most desktop platform lack this capability.
