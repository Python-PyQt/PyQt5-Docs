.. sip:class-description::
    :status: todo
    :brief: Method to play .wav sound files
    :digest: 951394ce3506fbf5130cd6123ee7da91

The :sip:ref:`~PyQt5.QtMultimedia.QSound` class provides a method to play .wav sound files.

Qt provides the most commonly required audio operation in GUI applications: asynchronously playing a sound file. This is most easily accomplished using the static :sip:ref:`~PyQt5.QtMultimedia.QSound.play` function:

.. literalinclude:: ../../../snippets/qtmultimedia-src-multimedia-doc-snippets-multimedia-snippets-qsound.py
    :lines: 59-59

Alternatively, create a :sip:ref:`~PyQt5.QtMultimedia.QSound` object from the sound file first and then call the :sip:ref:`~PyQt5.QtMultimedia.QSound.play` slot:

.. literalinclude:: ../../../snippets/qtmultimedia-src-multimedia-doc-snippets-multimedia-snippets-qsound.py
    :lines: 64-65

In both cases, the file may either be a local file or in a `resource <https://doc.qt.io/qt-5/resources.html>`_.

Once created a :sip:ref:`~PyQt5.QtMultimedia.QSound` object can be queried for its :sip:ref:`~PyQt5.QtMultimedia.QSound.fileName` and total number of :sip:ref:`~PyQt5.QtMultimedia.QSound.loops` (i.e. the number of times the sound will play). The number of repetitions can be altered using the :sip:ref:`~PyQt5.QtMultimedia.QSound.setLoops` function. While playing the sound, the :sip:ref:`~PyQt5.QtMultimedia.QSound.loopsRemaining` function returns the remaining number of repetitions. Use the :sip:ref:`~PyQt5.QtMultimedia.QSound.isFinished` function to determine whether the sound has finished playing.

Sounds played using a :sip:ref:`~PyQt5.QtMultimedia.QSound` object may use more memory than the static :sip:ref:`~PyQt5.QtMultimedia.QSound.play` function, but it may also play more immediately (depending on the underlying platform audio facilities).

If you require finer control over playing sounds, consider the :sip:ref:`~PyQt5.QtMultimedia.QSoundEffect` or :sip:ref:`~PyQt5.QtMultimedia.QAudioOutput` classes.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QSoundEffect`.
