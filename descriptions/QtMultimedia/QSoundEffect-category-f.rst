.. sip:method-description::
    :status: todo
    :pysig: 341be97d9aff90c9978347f66f945b77
    :realsig: () const
    :digest: f5f683866b5a8f9e822c6ab69a10c641

Returns the current *category* for this sound effect.

Some platforms can perform different audio routing for different categories, or may allow the user to set different volume levels for different categories.

This setting will be ignored on platforms that do not support audio categories.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QSoundEffect.setCategory`.
