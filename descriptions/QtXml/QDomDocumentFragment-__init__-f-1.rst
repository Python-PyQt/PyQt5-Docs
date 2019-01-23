.. sip:method-description::
    :status: todo
    :pysig: 2398a3d66e08176a61ad7a74f2a219b6
    :realsig: (const QDomDocumentFragment&)
    :digest: 463a6ccdea6058ee546a89411bf9f667

Constructs a copy of *x*.

The data of the copy is shared (shallow copy): modifying one node will also change the other. If you want to make a deep copy, use cloneNode().
