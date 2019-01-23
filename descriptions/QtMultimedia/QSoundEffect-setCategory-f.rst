.. sip:method-description::
    :status: todo
    :pysig: 341be97d9aff90c9978347f66f945b77
    :realsig: (const QString&)
    :digest: e92018efa1e34b64d74392422de8a26c

Sets the *category* of this sound effect to *category*.

Some platforms can perform different audio routing for different categories, or may allow the user to set different volume levels for different categories.

This setting will be ignored on platforms that do not support audio categories.

If this setting is changed while a sound effect is playing it will only take effect when the sound effect has stopped playing.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QSoundEffect.category`.
