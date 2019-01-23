.. sip:class-description::
    :status: todo
    :brief: IP address
    :digest: 950d42c196eda9afcb713bc5d9e744cd

The :sip:ref:`~PyQt5.QtNetwork.QHostAddress` class provides an IP address.

This class holds an IPv4 or IPv6 address in a platform- and protocol-independent manner.

:sip:ref:`~PyQt5.QtNetwork.QHostAddress` is normally used with the :sip:ref:`~PyQt5.QtNetwork.QTcpSocket`, :sip:ref:`~PyQt5.QtNetwork.QTcpServer`, and :sip:ref:`~PyQt5.QtNetwork.QUdpSocket` to connect to a host or to set up a server.

A host address is set with :sip:ref:`~PyQt5.QtNetwork.QHostAddress.setAddress`, and retrieved with :sip:ref:`~PyQt5.QtNetwork.QHostAddress.toIPv4Address`, :sip:ref:`~PyQt5.QtNetwork.QHostAddress.toIPv6Address`, or :sip:ref:`~PyQt5.QtNetwork.QHostAddress.toString`. You can check the type with :sip:ref:`~PyQt5.QtNetwork.QHostAddress.protocol`.

**Note:** Please note that :sip:ref:`~PyQt5.QtNetwork.QHostAddress` does not do DNS lookups. :sip:ref:`~PyQt5.QtNetwork.QHostInfo` is needed for that.

The class also supports common predefined addresses: :sip:ref:`~PyQt5.QtNetwork.QHostAddress.SpecialAddress.Null`, :sip:ref:`~PyQt5.QtNetwork.QHostAddress.SpecialAddress.LocalHost`, :sip:ref:`~PyQt5.QtNetwork.QHostAddress.SpecialAddress.LocalHostIPv6`, :sip:ref:`~PyQt5.QtNetwork.QHostAddress.SpecialAddress.Broadcast`, and :sip:ref:`~PyQt5.QtNetwork.QHostAddress.SpecialAddress.Any`.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QHostInfo`, :sip:ref:`~PyQt5.QtNetwork.QTcpSocket`, :sip:ref:`~PyQt5.QtNetwork.QTcpServer`, :sip:ref:`~PyQt5.QtNetwork.QUdpSocket`.
