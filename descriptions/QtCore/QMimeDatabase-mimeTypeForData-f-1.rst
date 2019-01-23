.. sip:method-description::
    :status: todo
    :pysig: f857ffe0d4b5161fcbb9f3bf58bbbe7a
    :realsig: (QIODevice*) const
    :digest: 75fddb1673665117e1a8ed688904948e

Returns a MIME type for the data in *device*.

A valid MIME type is always returned. If the data in *device* doesn't match any known MIME type data, the default MIME type (application/octet-stream) is returned.
