.. sip:method-description::
    :status: todo
    :pysig: c506ff134babdd6e68ab3e6350e95305
    :realsig: () const
    :digest: 995630a162fb5b916ba6bd58ade518e7

Returns ``true`` if this is a null variant, false otherwise. A variant is considered null if it contains no initialized value, or the contained value is a null pointer or is an instance of a built-in type that has an  method, in which case the result would be the same as calling  on the wrapped object.

**Warning:** Null variants is not a single state and two null variants may easily return ``false`` on the == operator if they do not contain similar null values.

.. seealso:: convert(int).
