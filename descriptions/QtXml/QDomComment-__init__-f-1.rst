.. sip:method-description::
    :status: todo
    :pysig: 57bc270a47d18187c43b7671fe2f2b10
    :realsig: (const QDomComment&)
    :digest: 463a6ccdea6058ee546a89411bf9f667

Constructs a copy of *x*.

The data of the copy is shared (shallow copy): modifying one node will also change the other. If you want to make a deep copy, use cloneNode().
