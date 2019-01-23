.. sip:method-description::
    :status: todo
    :pysig: 59d00075274e02360be7eaac03d8be33
    :realsig: (const QTextCursor&) const
    :digest: ae3776e529ef4f9fa6ad19b4a134e560

Returns ``true`` if this cursor and *other* are copies of each other, i.e. one of them was created as a copy of the other and neither has moved since. This is much stricter than equality.

.. seealso:: operator=(), operator==().
