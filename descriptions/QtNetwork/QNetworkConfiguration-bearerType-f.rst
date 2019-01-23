.. sip:method-description::
    :status: todo
    :pysig: ab5bcc35a57a7b2e617e1a8e34695774
    :realsig: () const
    :digest: 1dc4da82e7aa875b5ec707d48b1a1ce8

Returns the type of bearer used by this network configuration.

If the bearer type is :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.BearerType.BearerUnknown` the :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.bearerTypeName` function can be used to retrieve a textural type name for the bearer.

An invalid network configuration always returns the :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.BearerType.BearerUnknown` value.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkConfiguration.bearerTypeName`.
