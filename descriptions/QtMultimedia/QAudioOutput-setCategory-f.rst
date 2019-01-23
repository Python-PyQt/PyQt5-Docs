.. sip:method-description::
    :status: todo
    :pysig: 341be97d9aff90c9978347f66f945b77
    :realsig: (const QString&)
    :digest: 96d5f00b96488290c2cf7c4de04883b9

Sets the audio category of this audio stream to *category*.

Some platforms can group audio streams into categories and manage their volumes independently, or display them in a system mixer control. You can set this property to allow the platform to distinguish the purpose of your streams.

Not all platforms support audio stream categorization. In this case, the function call will be ignored.

Changing an audio output stream's category while it is opened will not take effect until it is reopened.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput.category`.
