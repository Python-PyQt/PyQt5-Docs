.. sip:method-description::
    :status: todo
    :pysig: 7f0a2137eedee5bbe1f85cb05972773a
    :realsig: (const QModelIndex&) const
    :digest: 6b309d69b04adb1668f10fb9aca2a3cd

Returns the item flags for the given *index*.

The base class implementation returns a combination of flags that enables the item (``ItemIsEnabled``) and allows it to be selected (``ItemIsSelectable``).

.. seealso:: Qt::ItemFlags.
