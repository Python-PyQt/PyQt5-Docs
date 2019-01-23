.. sip:method-description::
    :status: todo
    :pysig: bc433f34a736713d77fa06b4c6325f0a
    :realsig: (const QString&)
    :digest: b4ac8d2dacb808e0a8a748c91e93ee6a

Returns the first family name to be used whenever *familyName* is specified. The lookup is case insensitive.

If there is no substitution for *familyName*, *familyName* is returned.

To obtain a list of substitutions use :sip:ref:`~PyQt5.QtGui.QFont.substitutes`.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QFont.setFamily`, :sip:ref:`~PyQt5.QtGui.QFont.insertSubstitutions`, :sip:ref:`~PyQt5.QtGui.QFont.insertSubstitution`.
