.. sip:method-description::
    :status: todo
    :pysig: 6b4ec0c09210653836eac0355d7e1b26
    :realsig: () const
    :digest: d2139447233396ce151597cfc2f7d32b

Returns the broadcast address associated with the IPv4 address and netmask. It can usually be derived from those two by setting to 1 the bits of the IP address where the netmask contains a 0. (In other words, by bitwise-OR'ing the IP address with the inverse of the netmask)

This member is always empty for IPv6 addresses, since the concept of broadcast has been abandoned in that system in favor of multicast. In particular, the group of hosts corresponding to all the nodes in the local network can be reached by the "all-nodes" special multicast group (address FF02::1).

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkAddressEntry.setBroadcast`.
