.. sip:method-description::
    :status: todo
    :pysig: 2e57fad170d677379721ba5fe8dbdc6c
    :realsig: (const QUrl&) const
    :digest: e10f33d74b36fa4a2cbe4ed008b2b68b

Returns an invalid URL if the file *url* cannot be found. If the file exists, either the same url is returned or a different url if the file is located in a different namespace which is merged via a common virtual folder.
