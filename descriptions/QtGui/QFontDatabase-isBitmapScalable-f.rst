.. sip:method-description::
    :status: todo
    :pysig: f94934b8f6876698387386a0377ddcf2
    :realsig: (const QString&,const QString&) const
    :digest: 88183ff0006403e7566b1a6773869b44

Returns ``true`` if the font that has family *family* and style *style* is a scalable bitmap font; otherwise returns ``false``. Scaling a bitmap font usually produces an unattractive hardly readable result, because the pixels of the font are scaled. If you need to scale a bitmap font it is better to scale it to one of the fixed sizes returned by :sip:ref:`~PyQt5.QtGui.QFontDatabase.smoothSizes`.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QFontDatabase.isScalable`, :sip:ref:`~PyQt5.QtGui.QFontDatabase.isSmoothlyScalable`.
