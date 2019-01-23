:orphan:

.. sip:class:: PyQt5.QtCore.QCryptographicHash
    :description: QtCore/QCryptographicHash-c.rst

    .. sip:enum:: PyQt5.QtCore.QCryptographicHash.Algorithm
        :description: QtCore/QCryptographicHash-Algorithm-e.rst

        .. sip:enum-member:: PyQt5.QtCore.QCryptographicHash.Algorithm.Keccak_224
            :description: QtCore/QCryptographicHash-Algorithm-Keccak_224-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QCryptographicHash.Algorithm.Keccak_256
            :description: QtCore/QCryptographicHash-Algorithm-Keccak_256-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QCryptographicHash.Algorithm.Keccak_384
            :description: QtCore/QCryptographicHash-Algorithm-Keccak_384-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QCryptographicHash.Algorithm.Keccak_512
            :description: QtCore/QCryptographicHash-Algorithm-Keccak_512-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QCryptographicHash.Algorithm.Md4
            :description: QtCore/QCryptographicHash-Algorithm-Md4-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QCryptographicHash.Algorithm.Md5
            :description: QtCore/QCryptographicHash-Algorithm-Md5-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QCryptographicHash.Algorithm.Sha1
            :description: QtCore/QCryptographicHash-Algorithm-Sha1-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QCryptographicHash.Algorithm.Sha224
            :description: QtCore/QCryptographicHash-Algorithm-Sha224-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QCryptographicHash.Algorithm.Sha256
            :description: QtCore/QCryptographicHash-Algorithm-Sha256-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QCryptographicHash.Algorithm.Sha384
            :description: QtCore/QCryptographicHash-Algorithm-Sha384-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QCryptographicHash.Algorithm.Sha3_224
            :description: QtCore/QCryptographicHash-Algorithm-Sha3_224-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QCryptographicHash.Algorithm.Sha3_256
            :description: QtCore/QCryptographicHash-Algorithm-Sha3_256-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QCryptographicHash.Algorithm.Sha3_384
            :description: QtCore/QCryptographicHash-Algorithm-Sha3_384-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QCryptographicHash.Algorithm.Sha3_512
            :description: QtCore/QCryptographicHash-Algorithm-Sha3_512-v.rst

        .. sip:enum-member:: PyQt5.QtCore.QCryptographicHash.Algorithm.Sha512
            :description: QtCore/QCryptographicHash-Algorithm-Sha512-v.rst

    .. sip:method:: PyQt5.QtCore.QCryptographicHash.__init__
        :args:
            :sip:ref:`~PyQt5.QtCore.QCryptographicHash.Algorithm`
        :description: QtCore/QCryptographicHash-__init__-f.rst

    .. sip:method:: PyQt5.QtCore.QCryptographicHash.addData
        :args:
            bytes
        :description: QtCore/QCryptographicHash-addData-f.rst

    .. sip:method:: PyQt5.QtCore.QCryptographicHash.addData
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
        :description: QtCore/QCryptographicHash-addData-f-1.rst

    .. sip:method:: PyQt5.QtCore.QCryptographicHash.addData
        :args:
            :sip:ref:`~PyQt5.QtCore.QIODevice`
        :returns:
            bool
        :description: QtCore/QCryptographicHash-addData-f-2.rst

    .. sip:method:: PyQt5.QtCore.QCryptographicHash.hash
        :args:
            Union[:sip:ref:`~PyQt5.QtCore.QByteArray`, bytes, bytearray]
            :sip:ref:`~PyQt5.QtCore.QCryptographicHash.Algorithm`
        :returns:
            :sip:ref:`~PyQt5.QtCore.QByteArray`
        :static:
        :description: QtCore/QCryptographicHash-hash-f.rst

    .. sip:method:: PyQt5.QtCore.QCryptographicHash.hashLength
        :args:
            :sip:ref:`~PyQt5.QtCore.QCryptographicHash.Algorithm`
        :returns:
            int
        :static:
        :description: QtCore/QCryptographicHash-hashLength-f.rst

    .. sip:method:: PyQt5.QtCore.QCryptographicHash.reset
        :description: QtCore/QCryptographicHash-reset-f.rst

    .. sip:method:: PyQt5.QtCore.QCryptographicHash.result
        :returns:
            :sip:ref:`~PyQt5.QtCore.QByteArray`
        :description: QtCore/QCryptographicHash-result-f.rst
