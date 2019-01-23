.. sip:method-description::
    :status: todo
    :pysig: 8d0068c2a9176dcc273b16acdf1a9bf0
    :realsig: (const QObject*) const
    :digest: c79cf3d0358fad15902a487ddeb2cc23

Returns ``true`` if this property is designable for the given *object*; otherwise returns ``false``.

If no *object* is given, the function returns ``false`` if the ``Q_PROPERTY()``'s ``DESIGNABLE`` attribute is false; otherwise returns ``true`` (if the attribute is true or is a function or expression).

.. seealso:: :sip:ref:`~PyQt5.QtCore.QMetaProperty.isScriptable`, :sip:ref:`~PyQt5.QtCore.QMetaProperty.isStored`.
