.. sip:method-description::
    :status: todo
    :pysig: e21ba672cbc4592dfd21e8915b9c19ff
    :realsig: (const QDomDocument&)
    :digest: 463a6ccdea6058ee546a89411bf9f667

Constructs a copy of *x*.

The data of the copy is shared (shallow copy): modifying one node will also change the other. If you want to make a deep copy, use cloneNode().
