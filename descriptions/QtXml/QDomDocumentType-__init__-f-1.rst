.. sip:method-description::
    :status: todo
    :pysig: 32a4afce7af66638f334bfa25a634673
    :realsig: (const QDomDocumentType&)
    :digest: 61022c17cc1de5fbfaecabb4ebfa4c6f

Constructs a copy of *n*.

The data of the copy is shared (shallow copy): modifying one node will also change the other. If you want to make a deep copy, use cloneNode().
