:orphan:

.. sip:class:: PyQt5.QtWebEngineCore.QWebEngineUrlScheme
    :description: QtWebEngineCore/QWebEngineUrlScheme-c.rst

    .. sip:enum:: PyQt5.QtWebEngineCore.QWebEngineUrlScheme.Flag
        :description: QtWebEngineCore/QWebEngineUrlScheme-Flag-e.rst

        .. sip:enum-member:: PyQt5.QtWebEngineCore.QWebEngineUrlScheme.Flag.ContentSecurityPolicyIgnored
            :description: QtWebEngineCore/QWebEngineUrlScheme-Flag-ContentSecurityPolicyIgnored-v.rst

        .. sip:enum-member:: PyQt5.QtWebEngineCore.QWebEngineUrlScheme.Flag.CorsEnabled
            :description: QtWebEngineCore/QWebEngineUrlScheme-Flag-CorsEnabled-v.rst

        .. sip:enum-member:: PyQt5.QtWebEngineCore.QWebEngineUrlScheme.Flag.LocalAccessAllowed
            :description: QtWebEngineCore/QWebEngineUrlScheme-Flag-LocalAccessAllowed-v.rst

        .. sip:enum-member:: PyQt5.QtWebEngineCore.QWebEngineUrlScheme.Flag.LocalScheme
            :description: QtWebEngineCore/QWebEngineUrlScheme-Flag-LocalScheme-v.rst

        .. sip:enum-member:: PyQt5.QtWebEngineCore.QWebEngineUrlScheme.Flag.NoAccessAllowed
            :description: QtWebEngineCore/QWebEngineUrlScheme-Flag-NoAccessAllowed-v.rst

        .. sip:enum-member:: PyQt5.QtWebEngineCore.QWebEngineUrlScheme.Flag.SecureScheme
            :description: QtWebEngineCore/QWebEngineUrlScheme-Flag-SecureScheme-v.rst

        .. sip:enum-member:: PyQt5.QtWebEngineCore.QWebEngineUrlScheme.Flag.ServiceWorkersAllowed
            :description: QtWebEngineCore/QWebEngineUrlScheme-Flag-ServiceWorkersAllowed-v.rst

        .. sip:enum-member:: PyQt5.QtWebEngineCore.QWebEngineUrlScheme.Flag.ViewSourceAllowed
            :description: QtWebEngineCore/QWebEngineUrlScheme-Flag-ViewSourceAllowed-v.rst

    .. sip:enum:: PyQt5.QtWebEngineCore.QWebEngineUrlScheme.SpecialPort
        :description: QtWebEngineCore/QWebEngineUrlScheme-SpecialPort-e.rst

        .. sip:enum-member:: PyQt5.QtWebEngineCore.QWebEngineUrlScheme.SpecialPort.PortUnspecified
            :description: QtWebEngineCore/QWebEngineUrlScheme-SpecialPort-PortUnspecified-v.rst

    .. sip:enum:: PyQt5.QtWebEngineCore.QWebEngineUrlScheme.Syntax
        :description: QtWebEngineCore/QWebEngineUrlScheme-Syntax-e.rst

        .. sip:enum-member:: PyQt5.QtWebEngineCore.QWebEngineUrlScheme.Syntax.Host
            :description: QtWebEngineCore/QWebEngineUrlScheme-Syntax-Host-v.rst

        .. sip:enum-member:: PyQt5.QtWebEngineCore.QWebEngineUrlScheme.Syntax.HostAndPort
            :description: QtWebEngineCore/QWebEngineUrlScheme-Syntax-HostAndPort-v.rst

        .. sip:enum-member:: PyQt5.QtWebEngineCore.QWebEngineUrlScheme.Syntax.HostPortAndUserInformation
            :description: QtWebEngineCore/QWebEngineUrlScheme-Syntax-HostPortAndUserInformation-v.rst

        .. sip:enum-member:: PyQt5.QtWebEngineCore.QWebEngineUrlScheme.Syntax.Path
            :description: QtWebEngineCore/QWebEngineUrlScheme-Syntax-Path-v.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineUrlScheme.__init__
        :description: QtWebEngineCore/QWebEngineUrlScheme-__init__-f.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineUrlScheme.__init__
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :description: QtWebEngineCore/QWebEngineUrlScheme-__init__-f-1.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineUrlScheme.__init__
        :args:
            :sip:ref:`~PyQt5.QtWebEngineCore.QWebEngineUrlScheme`
        :description: QtWebEngineCore/QWebEngineUrlScheme-__init__-f-2.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineUrlScheme.defaultPort
        :returns:
            int
        :description: QtWebEngineCore/QWebEngineUrlScheme-defaultPort-f.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineUrlScheme.__eq__
        :args:
            :sip:ref:`~PyQt5.QtWebEngineCore.QWebEngineUrlScheme`
        :returns:
            bool
        :description: QtWebEngineCore/QWebEngineUrlScheme-__eq__-f.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineUrlScheme.flags
        :returns:
            :sip:ref:`~PyQt5.QtWebEngineCore.QWebEngineUrlScheme.Flags`
        :description: QtWebEngineCore/QWebEngineUrlScheme-flags-f.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineUrlScheme.name
        :returns:
            :sip:ref:`~PyQt5.QtCore.QByteArray`
        :description: QtWebEngineCore/QWebEngineUrlScheme-name-f.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineUrlScheme.__ne__
        :args:
            :sip:ref:`~PyQt5.QtWebEngineCore.QWebEngineUrlScheme`
        :returns:
            bool
        :description: QtWebEngineCore/QWebEngineUrlScheme-__ne__-f.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineUrlScheme.registerScheme
        :args:
            :sip:ref:`~PyQt5.QtWebEngineCore.QWebEngineUrlScheme`
        :static:
        :description: QtWebEngineCore/QWebEngineUrlScheme-registerScheme-f.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineUrlScheme.schemeByName
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :returns:
            :sip:ref:`~PyQt5.QtWebEngineCore.QWebEngineUrlScheme`
        :static:
        :description: QtWebEngineCore/QWebEngineUrlScheme-schemeByName-f.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineUrlScheme.setDefaultPort
        :args:
            int
        :description: QtWebEngineCore/QWebEngineUrlScheme-setDefaultPort-f.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineUrlScheme.setFlags
        :args:
            Union[:sip:ref:`~PyQt5.QtWebEngineCore.QWebEngineUrlScheme.Flags`, :sip:ref:`~PyQt5.QtWebEngineCore.QWebEngineUrlScheme.Flag`]
        :description: QtWebEngineCore/QWebEngineUrlScheme-setFlags-f.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineUrlScheme.setName
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :description: QtWebEngineCore/QWebEngineUrlScheme-setName-f.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineUrlScheme.setSyntax
        :args:
            :sip:ref:`~PyQt5.QtWebEngineCore.QWebEngineUrlScheme.Syntax`
        :description: QtWebEngineCore/QWebEngineUrlScheme-setSyntax-f.rst

    .. sip:method:: PyQt5.QtWebEngineCore.QWebEngineUrlScheme.syntax
        :returns:
            :sip:ref:`~PyQt5.QtWebEngineCore.QWebEngineUrlScheme.Syntax`
        :description: QtWebEngineCore/QWebEngineUrlScheme-syntax-f.rst
