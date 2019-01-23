.. sip:enum-member-description::
    :status: todo
    :value: 0x0000006
    :digest: fe3363a13141eccf7e5ae9c27d7c7ddd

A discovered configuration can be immediately used to create a new :sip:ref:`~PyQt5.QtNetwork.QNetworkSession`. An example of a discovered configuration could be a WLAN which is within in range. If the device moves out of range the discovered flag is dropped. A second example is a GPRS configuration which generally remains discovered for as long as the device has network coverage. A configuration that has this state is also in state . If the configuration is a service network this flag is set if at least one of the underlying access points configurations has the Discovered state.
