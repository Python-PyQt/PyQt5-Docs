.. sip:class-description::
    :status: todo
    :brief: Interface to the systems analog radio device
    :digest: 7befe58b0ee4cc2121cc8aa08436f5f6

The :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner` class provides an interface to the systems analog radio device.

You can control the systems analog radio device using this interface, for example:

.. literalinclude:: ../../../snippets/qtmultimedia-src-multimedia-doc-snippets-multimedia-snippets-media.py
    :lines: 244-251

The radio object will emit signals for any changes in state such as: :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.bandChanged`, :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.frequencyChanged`, :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.stereoStatusChanged`, :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.searchingChanged`, :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.signalStrengthChanged`, :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.volumeChanged`, :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.mutedChanged`.

You can change between the frequency bands using :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.setBand` however it is recommended that you check to make sure the band is available first using :sip:ref:`~PyQt5.QtMultimedia.QRadioTuner.isBandSupported`.

.. seealso:: :sip:ref:`~PyQt5.QtMultimedia.QRadioData`, `Radio Overview <https://doc.qt.io/qt-5/radiooverview.html>`_.
