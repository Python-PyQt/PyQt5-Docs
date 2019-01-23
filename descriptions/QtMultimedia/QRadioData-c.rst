.. sip:class-description::
    :status: todo
    :brief: Interfaces to the RDS functionality of the system radio
    :digest: 0afd8304fc7f2e3a11e92cb9a5f0705e

The :sip:ref:`~PyQt5.QtMultimedia.QRadioData` class provides interfaces to the RDS functionality of the system radio.

The radio data object will emit signals for any changes in radio data. You can enable or disable alternative frequency with :sip:ref:`~PyQt5.QtMultimedia.QRadioData.setAlternativeFrequenciesEnabled`.

You can get a :sip:ref:`~PyQt5.QtMultimedia.QRadioData` instance fromt the :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.radioData` property from a :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner` instance.

.. literalinclude:: ../../../snippets/qtmultimedia-src-multimedia-doc-snippets-multimedia-snippets-media.py
    :lines: 255-256

Alternatively, you can pass an instance of :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner` to the constructor to :sip:ref:`~PyQt5.QtMultimedia.QRadioData`.

.. seealso:: `Radio Overview <https://doc.qt.io/qt-5/radiooverview.html>`_.
