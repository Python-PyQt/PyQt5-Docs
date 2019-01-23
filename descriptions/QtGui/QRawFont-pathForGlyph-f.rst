.. sip:method-description::
    :status: todo
    :pysig: 7a2ad606a5426cce7ea55db8cf25f9a4
    :realsig: (quint32) const
    :digest: 6c79e859fafed46d83505688c649aa90

This function returns the shape of the glyph at a given *glyphIndex* in the underlying font if the :sip:ref:`~PyQt5.QtGui.QRawFont` is valid. Otherwise, it returns an empty :sip:ref:`~PyQt5.QtGui.QPainterPath`.

The returned glyph will always be unhinted.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QRawFont.alphaMapForGlyph`.
