.. sip:class-description::
    :status: todo
    :brief: Specifies that a host supports HTTP Strict Transport Security policy (HSTS)
    :digest: e66f6a186a412a75571c82501173f27d

The :sip:ref:`~PyQt5.QtNetwork.QHstsPolicy` class specifies that a host supports HTTP Strict Transport Security policy (HSTS).

HSTS policy defines a period of time during which :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager` should only access a host in a secure fashion. HSTS policy is defined by RFC6797.

You can set expiry time and host name for this policy, and control whether it applies to subdomains, either in the constructor or by calling :sip:ref:`~PyQt5.QtNetwork.QHstsPolicy.setExpiry`, setHost() and setIncludesSubdomains().

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkAccessManager.setStrictTransportSecurityEnabled`.
