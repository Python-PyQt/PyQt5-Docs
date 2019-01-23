.. sip:method-description::
    :status: todo
    :pysig: 341be97d9aff90c9978347f66f945b77
    :realsig: () const
    :digest: eff3642f51f69529f25fe61805f1c0b4

Returns the audio category of this audio stream.

Some platforms can group audio streams into categories and manage their volumes independently, or display them in a system mixer control. You can set this property to allow the platform to distinguish the purpose of your streams.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput.setCategory`.
