.. sip:method-description::
    :status: todo
    :pysig: 5ed6564e04baeb415c79f7f81528fb64
    :realsig: (const QDomCDATASection&)
    :digest: 463a6ccdea6058ee546a89411bf9f667

Constructs a copy of *x*.

The data of the copy is shared (shallow copy): modifying one node will also change the other. If you want to make a deep copy, use cloneNode().
