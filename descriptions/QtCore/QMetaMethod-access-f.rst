.. sip:method-description::
    :status: todo
    :pysig: 63a230ccf50cc619c70c673b2c87fc15
    :realsig: () const
    :digest: 7c59003abd06127d3b5ad4680099bbfc

Returns the access specification of this method (private, protected, or public).

**Note:** Signals are always public, but you should regard that as an implementation detail. It is almost always a bad idea to emit a signal from outside its class.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QMetaMethod.methodType`.
