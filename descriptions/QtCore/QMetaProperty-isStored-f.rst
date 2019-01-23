.. sip:method-description::
    :status: todo
    :pysig: 8d0068c2a9176dcc273b16acdf1a9bf0
    :realsig: (const QObject*) const
    :digest: 4511554ae85e10b628ee1db9b761e5bd

Returns ``true`` if the property is stored for *object*; otherwise returns false.

If no *object* is given, the function returns ``false`` if the ``Q_PROPERTY()``'s ``STORED`` attribute is false; otherwise returns true (if the attribute is true or is a function or expression).

.. seealso:: :sip:ref:`~PyQt5.QtCore.QMetaProperty.isDesignable`, :sip:ref:`~PyQt5.QtCore.QMetaProperty.isScriptable`.
