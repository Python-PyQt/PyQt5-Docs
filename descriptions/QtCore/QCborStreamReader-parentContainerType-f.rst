.. sip:method-description::
    :status: todo
    :pysig: 7920231dda295242fd341ab42c65c870
    :realsig: () const
    :digest: be7366d7cd0ce43d03bb7353e4e4b817

Returns either QCborStreamReader::Array or QCborStreamReader::Map, indicating whether the container that contains the current item was an array or map, respectively. If we're currently parsing the root element, this function returns QCborStreamReader::Invalid.

.. seealso:: containerDepth()enterContainer().
