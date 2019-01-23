.. sip:method-description::
    :status: todo
    :pysig: fe71d6f3f8509b61c8f8848cb00692e9
    :realsig: (const QDomEntity&)
    :digest: 463a6ccdea6058ee546a89411bf9f667

Constructs a copy of *x*.

The data of the copy is shared (shallow copy): modifying one node will also change the other. If you want to make a deep copy, use cloneNode().
