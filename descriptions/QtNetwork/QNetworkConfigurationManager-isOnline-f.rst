.. sip:method-description::
    :status: todo
    :pysig: c506ff134babdd6e68ab3e6350e95305
    :realsig: () const
    :digest: dd4b84703532d037b6bd131205dc36a7

Returns ``true`` if the system is considered to be connected to another device via an active network interface; otherwise returns ``false``.

This is equivalent to the following code snippet:

.. literalinclude:: ../../../snippets/qtbase-src-network-doc-snippets-code-src_network_bearer_qnetworkconfigmanager.py
    :lines: 54-59

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkConfigurationManager.onlineStateChanged`.
