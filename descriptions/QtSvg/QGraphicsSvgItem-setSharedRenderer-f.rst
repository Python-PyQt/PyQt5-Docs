.. sip:method-description::
    :status: todo
    :pysig: d49c5ad1142c895e4a46b00dd6fdd512
    :realsig: (QSvgRenderer*)
    :digest: 4864eaa32590272dc5d172dcfc22af17

Sets *renderer* to be a shared :sip:ref:`~PyQt5.QtSvg.QSvgRenderer` on the item. By using this method one can share the same :sip:ref:`~PyQt5.QtSvg.QSvgRenderer` on a number of items. This means that the SVG file will be parsed only once. :sip:ref:`~PyQt5.QtSvg.QSvgRenderer` passed to this method has to exist for as long as this item is used.
