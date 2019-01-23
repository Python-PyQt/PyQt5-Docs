.. sip:method-description::
    :status: todo
    :pysig: 2cc8f0df6b41c199a0b762c15d9e2b16
    :realsig: (const QModelIndex&) const
    :digest: 24c0064da964bb582801db0102336e5d

Returns ``true`` if the value at the index *index* is dirty, otherwise false. Dirty values are values that were modified in the model but not yet written into the database.

If *index* is invalid or points to a non-existing row, false is returned.
