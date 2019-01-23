.. sip:method-description::
    :status: todo
    :pysig: 1843fe9aa5e65beb3cf3b149ae1ae1f6
    :realsig: (Qt::TextFormat)
    :digest: 1f666707d8d79e84bb5421c38a836af0

Sets the text format of the :sip:ref:`~PyQt5.QtGui.QStaticText` to *textFormat*. If *textFormat* is set to :sip:ref:`~PyQt5.QtCore.Qt.TextFormat.AutoText` (the default), the format of the text will try to be determined using the function Qt::mightBeRichText(). If the text format is :sip:ref:`~PyQt5.QtCore.Qt.TextFormat.PlainText`, then the text will be displayed as is, whereas it will be interpreted as HTML if the format is :sip:ref:`~PyQt5.QtCore.Qt.TextFormat.RichText`. HTML tags that alter the font of the text, its color, or its layout are supported by :sip:ref:`~PyQt5.QtGui.QStaticText`.

**Note:** This function will cause the layout of the text to require recalculation.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QStaticText.textFormat`, :sip:ref:`~PyQt5.QtGui.QStaticText.text`.
