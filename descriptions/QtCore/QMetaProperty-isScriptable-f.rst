.. sip:method-description::
    :status: todo
    :pysig: 8d0068c2a9176dcc273b16acdf1a9bf0
    :realsig: (const QObject*) const
    :digest: e980feeb430b82142f8655dac3ee0a50

Returns ``true`` if the property is scriptable for the given *object*; otherwise returns ``false``.

If no *object* is given, the function returns ``false`` if the ``Q_PROPERTY()``'s ``SCRIPTABLE`` attribute is false; otherwise returns true (if the attribute is true or is a function or expression).

.. seealso:: :sip:ref:`~PyQt5.QtCore.QMetaProperty.isDesignable`, :sip:ref:`~PyQt5.QtCore.QMetaProperty.isStored`.
