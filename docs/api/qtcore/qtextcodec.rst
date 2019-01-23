:orphan:

.. sip:class:: PyQt5.QtCore.QTextCodec
    :description: QtCore/QTextCodec-c.rst

    .. sip:enum:: PyQt5.QtCore.QTextCodec.ConversionFlag
        :description: QtCore/QTextCodec-ConversionFlag-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QTextCodec.ConversionFlag.ConvertInvalidToNull
            :description: QtCore/QTextCodec-ConversionFlag-ConvertInvalidToNull-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QTextCodec.ConversionFlag.DefaultConversion
            :description: QtCore/QTextCodec-ConversionFlag-DefaultConversion-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QTextCodec.ConversionFlag.IgnoreHeader
            :description: QtCore/QTextCodec-ConversionFlag-IgnoreHeader-v.rst

    .. sip:method:: PyQt5.QtCore.QTextCodec.__init__
        :description: QtCore/QTextCodec-__init__-f.rst

    .. sip:method:: PyQt5.QtCore.QTextCodec.aliases
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QByteArray`]
        :description: QtCore/QTextCodec-aliases-f.rst

    .. sip:method:: PyQt5.QtCore.QTextCodec.availableCodecs
        :returns:
            List[:sip:ref:`~PyQt5.QtCore.QByteArray`]
        :static:
        :description: QtCore/QTextCodec-availableCodecs-f.rst

    .. sip:method:: PyQt5.QtCore.QTextCodec.availableMibs
        :returns:
            List[int]
        :static:
        :description: QtCore/QTextCodec-availableMibs-f.rst

    .. sip:method:: PyQt5.QtCore.QTextCodec.canEncode
        :args:
            str
        :returns:
            bool
        :description: QtCore/QTextCodec-canEncode-f.rst

    .. sip:method:: PyQt5.QtCore.QTextCodec.codecForHtml
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :returns:
            :sip:ref:`~PyQt5.QtCore.QTextCodec`
        :static:
        :description: QtCore/QTextCodec-codecForHtml-f.rst

    .. sip:method:: PyQt5.QtCore.QTextCodec.codecForHtml
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
            :sip:ref:`~PyQt5.QtCore.QTextCodec`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QTextCodec`
        :static:
        :description: QtCore/QTextCodec-codecForHtml-f-1.rst

    .. sip:method:: PyQt5.QtCore.QTextCodec.codecForLocale
        :returns:
            :sip:ref:`~PyQt5.QtCore.QTextCodec`
        :static:
        :description: QtCore/QTextCodec-codecForLocale-f.rst

    .. sip:method:: PyQt5.QtCore.QTextCodec.codecForMib
        :args:
            int
        :returns:
            :sip:ref:`~PyQt5.QtCore.QTextCodec`
        :static:
        :description: QtCore/QTextCodec-codecForMib-f.rst

    .. sip:method:: PyQt5.QtCore.QTextCodec.codecForName
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :returns:
            :sip:ref:`~PyQt5.QtCore.QTextCodec`
        :static:
        :description: QtCore/QTextCodec-codecForName-f.rst

    .. sip:method:: PyQt5.QtCore.QTextCodec.codecForName
        :args:
            str
        :returns:
            :sip:ref:`~PyQt5.QtCore.QTextCodec`
        :static:
        :description: QtCore/QTextCodec-codecForName-f-1.rst

    .. sip:method:: PyQt5.QtCore.QTextCodec.codecForUtfText
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :returns:
            :sip:ref:`~PyQt5.QtCore.QTextCodec`
        :static:
        :description: QtCore/QTextCodec-codecForUtfText-f.rst

    .. sip:method:: PyQt5.QtCore.QTextCodec.codecForUtfText
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
            :sip:ref:`~PyQt5.QtCore.QTextCodec`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QTextCodec`
        :static:
        :description: QtCore/QTextCodec-codecForUtfText-f-1.rst

    .. sip:method:: PyQt5.QtCore.QTextCodec.convertToUnicode
        :args:
            bytes
            :sip:ref:`~PyQt5.QtCore.QTextCodec.ConverterState`
        :returns:
            str
        :description: QtCore/QTextCodec-convertToUnicode-f.rst

    .. sip:method:: PyQt5.QtCore.QTextCodec.fromUnicode
        :args:
            str
        :returns:
            :sip:ref:`~PyQt5.QtCore.QByteArray`
        :description: QtCore/QTextCodec-fromUnicode-f.rst

    .. sip:method:: PyQt5.QtCore.QTextCodec.makeDecoder
        :args:
            flags: Union[:sip:ref:`~PyQt5.QtCore.QTextCodec.ConversionFlags`, :sip:ref:`~PyQt5.QtCore.QTextCodec.ConversionFlag`] = :sip:ref:`~PyQt5.QtCore.QTextCodec.ConversionFlag.DefaultConversion`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QTextDecoder`
        :description: QtCore/QTextCodec-makeDecoder-f.rst

    .. sip:method:: PyQt5.QtCore.QTextCodec.makeEncoder
        :args:
            flags: Union[:sip:ref:`~PyQt5.QtCore.QTextCodec.ConversionFlags`, :sip:ref:`~PyQt5.QtCore.QTextCodec.ConversionFlag`] = :sip:ref:`~PyQt5.QtCore.QTextCodec.ConversionFlag.DefaultConversion`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QTextEncoder`
        :description: QtCore/QTextCodec-makeEncoder-f.rst

    .. sip:method:: PyQt5.QtCore.QTextCodec.mibEnum
        :returns:
            int
        :description: QtCore/QTextCodec-mibEnum-f.rst

    .. sip:method:: PyQt5.QtCore.QTextCodec.name
        :returns:
            :sip:ref:`~PyQt5.QtCore.QByteArray`
        :description: QtCore/QTextCodec-name-f.rst

    .. sip:method:: PyQt5.QtCore.QTextCodec.setCodecForLocale
        :args:
            :sip:ref:`~PyQt5.QtCore.QTextCodec`
        :static:
        :description: QtCore/QTextCodec-setCodecForLocale-f.rst

    .. sip:method:: PyQt5.QtCore.QTextCodec.toUnicode
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :returns:
            str
        :description: QtCore/QTextCodec-toUnicode-f.rst

    .. sip:method:: PyQt5.QtCore.QTextCodec.toUnicode
        :args:
            str
        :returns:
            str
        :description: QtCore/QTextCodec-toUnicode-f-1.rst

    .. sip:method:: PyQt5.QtCore.QTextCodec.toUnicode
        :args:
            bytes
            state: :sip:ref:`~PyQt5.QtCore.QTextCodec.ConverterState` = None
        :returns:
            str
        :description: QtCore/QTextCodec-toUnicode-f-2.rst
