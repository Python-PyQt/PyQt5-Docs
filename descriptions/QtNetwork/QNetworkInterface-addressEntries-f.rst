.. sip:method-description::
    :status: todo
    :pysig: 79b495522ccbae9d26315096d56b3a46
    :realsig: () const
    :digest: d9986d41c1cb860c3757ac2022c9d84a

Returns the list of IP addresses that this interface possesses along with their associated netmasks and broadcast addresses.

If the netmask or broadcast address or other information is not necessary, you can call the :sip:ref:`~PyQt5.QtNetwork.QNetworkInterface.allAddresses` function to obtain just the IP addresses of the active interfaces.
