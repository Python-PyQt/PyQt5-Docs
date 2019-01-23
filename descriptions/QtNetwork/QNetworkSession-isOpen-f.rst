.. sip:method-description::
    :status: todo
    :pysig: c506ff134babdd6e68ab3e6350e95305
    :realsig: () const
    :digest: 395b093f8c1b50a77821b0f48ef86328

Returns ``true`` if this session is open. If the number of all open sessions is greater than zero the underlying network interface will remain connected/up.

The session can be controlled via :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.open` and :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.close`.
