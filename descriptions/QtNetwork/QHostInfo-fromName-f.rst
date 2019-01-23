.. sip:method-description::
    :status: todo
    :pysig: c6a1a56a81ee5082db67417333f49242
    :realsig: (const QString&)
    :digest: f112b9e32dde2a17686aae9ee0444442

Looks up the IP address(es) for the given host *name*. The function blocks during the lookup which means that execution of the program is suspended until the results of the lookup are ready. Returns the result of the lookup in a :sip:ref:`~PyQt5.QtNetwork.QHostInfo` object.

If you pass a literal IP address to *name* instead of a host name, :sip:ref:`~PyQt5.QtNetwork.QHostInfo` will search for the domain name for the IP (i.e., :sip:ref:`~PyQt5.QtNetwork.QHostInfo` will perform a *reverse* lookup). On success, the returned :sip:ref:`~PyQt5.QtNetwork.QHostInfo` will contain both the resolved domain name and IP addresses for the host name.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QHostInfo.lookupHost`.
