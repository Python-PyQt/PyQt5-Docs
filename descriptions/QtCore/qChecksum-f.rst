.. sip:method-description::
    :status: todo
    :pysig: 1512a78beed0c522a2fd3dcdf28d9ecd
    :realsig: (const char*,uint)
    :digest: 8b1e6762b0a59314b892a0c293cfba30

Returns the CRC-16 checksum of the first *len* bytes of *data*.

The checksum is independent of the byte order (endianness) and will be calculated accorded to the algorithm published in ISO 3309 (Qt::ChecksumIso3309).

**Note:** This function is a 16-bit cache conserving (16 entry table) implementation of the CRC-16-CCITT algorithm.
