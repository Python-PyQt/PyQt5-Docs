.. sip:enum-description::
    :status: todo
    :digest: 812f07af1bea99dd51ab116f504f55e2

**Note:** In Qt versions before 5.9, when asked to generate a SHA3 hash sum, :sip:ref:`~PyQt5.QtCore.QCryptographicHash` actually calculated Keccak. If you need compatibility with SHA-3 hashes produced by those versions of Qt, use the ``Keccak_`` enumerators. Alternatively, if source compatibility is required, define the macro ``QT_SHA3_KECCAK_COMPAT``.
