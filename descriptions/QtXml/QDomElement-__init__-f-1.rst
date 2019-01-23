.. sip:method-description::
    :status: todo
    :pysig: 78a9a56976007b29b75640ce80ffece3
    :realsig: (const QDomElement&)
    :digest: 463a6ccdea6058ee546a89411bf9f667

Constructs a copy of *x*.

The data of the copy is shared (shallow copy): modifying one node will also change the other. If you want to make a deep copy, use cloneNode().
