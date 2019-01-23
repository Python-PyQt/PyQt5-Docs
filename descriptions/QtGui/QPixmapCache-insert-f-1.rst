.. sip:method-description::
    :status: todo
    :pysig: f15e47b88e3f54f9e9a64b3fcebb0404
    :realsig: (const QString&,const QPixmap&)
    :digest: a58d9656c2c61a1bdf0305f5d4167658

Inserts a copy of the pixmap *pixmap* associated with the *key* into the cache.

All pixmaps inserted by the Qt library have a key starting with "$qt", so your own pixmap keys should never begin "$qt".

When a pixmap is inserted and the cache is about to exceed its limit, it removes pixmaps until there is enough room for the pixmap to be inserted.

The oldest pixmaps (least recently accessed in the cache) are deleted when more space is needed.

The function returns ``true`` if the object was inserted into the cache; otherwise it returns ``false``.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QPixmapCache.setCacheLimit`.
