.. sip:method-description::
    :status: todo
    :pysig: 041b588ea5b9e86c50645d15e658deee
    :realsig: () const
    :digest: ce2c400918fb402305ac1c262fd6a63f

Returns all sub configurations of this network configuration in priority order. The first sub configuration in the list has the highest priority.

Only network configurations of type :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.Type.ServiceNetwork` can have children. Otherwise this function returns an empty list.
