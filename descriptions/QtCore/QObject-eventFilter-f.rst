.. sip:method-description::
    :status: todo
    :pysig: 654031b83cf8a95868c6ce1b058d93fe
    :realsig: (QObject*,QEvent*)
    :digest: 7a3c93335d4c0d2918bcaace974c5e89

Filters events if this object has been installed as an event filter for the *watched* object.

In your reimplementation of this function, if you want to filter the *event* out, i.e. stop it being handled further, return true; otherwise return false.

Example:

.. literalinclude:: ../../../snippets/qtbase-src-corelib-doc-snippets-code-src_corelib_kernel_qobject.py
    :lines: 100-134

Notice in the example above that unhandled events are passed to the base class's  function, since the base class might have reimplemented  for its own internal purposes.

**Warning:** If you delete the receiver object in this function, be sure to return true. Otherwise, Qt will forward the event to the deleted object and the program might crash.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QObject.installEventFilter`.
