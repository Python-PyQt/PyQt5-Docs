.. sip:method-description::
    :status: todo
    :pysig: 09e27b40a0bd2c0f2879cff2ca3dd76b
    :realsig: (const QDomCharacterData&)
    :digest: 463a6ccdea6058ee546a89411bf9f667

Constructs a copy of *x*.

The data of the copy is shared (shallow copy): modifying one node will also change the other. If you want to make a deep copy, use cloneNode().
