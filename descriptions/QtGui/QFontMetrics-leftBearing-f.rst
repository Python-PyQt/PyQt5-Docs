.. sip:method-description::
    :status: todo
    :pysig: 0f9b0ea7a3407ca50e1df7b110b9ad1f
    :realsig: (QChar) const
    :digest: 84fea581a8e25f777dd14b07a45e2c94

Returns the left bearing of character *ch* in the font.

The left bearing is the right-ward distance of the left-most pixel of the character from the logical origin of the character. This value is negative if the pixels of the character extend to the left of the logical origin.

See :sip:ref:`~PyQt5.QtGui.QFontMetrics.width` for a graphical description of this metric.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QFontMetrics.rightBearing`, :sip:ref:`~PyQt5.QtGui.QFontMetrics.minLeftBearing`, :sip:ref:`~PyQt5.QtGui.QFontMetrics.width`.
