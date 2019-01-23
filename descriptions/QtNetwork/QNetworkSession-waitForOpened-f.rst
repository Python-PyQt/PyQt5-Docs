.. sip:method-description::
    :status: todo
    :pysig: 4ebcca4b876ddf43aac5582e04e14a68
    :realsig: (int)
    :digest: 5da85c28f3fbd46a3cbfb1e5b9faa0b2

Waits until the session has been opened, up to *msecs* milliseconds. If the session has been opened, this function returns ``true``; otherwise it returns ``false``. In the case where it returns ``false``, you can call :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.error` to determine the cause of the error.

The following example waits up to one second for the session to be opened:

.. literalinclude:: ../../../snippets/qtbase-src-network-doc-snippets-code-src_network_bearer_qnetworksession.py
    :lines: 43-45

If *msecs* is -1, this function will not time out.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.open`, :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.error`.
