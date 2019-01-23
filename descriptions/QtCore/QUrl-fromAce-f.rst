.. sip:method-description::
    :status: todo
    :pysig: 03249c7acded8b60b06ef6f330037463
    :realsig: (const QByteArray&)
    :digest: dccad07fd4e3d9b160a63fe518bab2f6

Returns the Unicode form of the given domain name *domain*, which is encoded in the ASCII Compatible Encoding (ACE). The result of this function is considered equivalent to *domain*.

If the value in *domain* cannot be encoded, it will be converted to QString and returned.

The ASCII Compatible Encoding (ACE) is defined by RFC 3490, RFC 3491 and RFC 3492. It is part of the Internationalizing Domain Names in Applications (IDNA) specification, which allows for domain names (like ``"example.com"``) to be written using international characters.
