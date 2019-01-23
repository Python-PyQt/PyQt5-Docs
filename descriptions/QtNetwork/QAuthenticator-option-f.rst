.. sip:method-description::
    :status: todo
    :pysig: 9064598f6881fe97156ec2e9c47c55cf
    :realsig: (const QString&) const
    :digest: 1d1f1ef6b63e07a7493f17d56589943b

Returns the value related to option *opt* if it was set by the server. See the Options section for more information on incoming options. If option *opt* isn't found, an invalid :sip:ref:`~PyQt5.QtCore.QVariant` will be returned.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QAuthenticator.setOption`, :sip:ref:`~PyQt5.QtNetwork.QAuthenticator.options`, QAuthenticator options.
