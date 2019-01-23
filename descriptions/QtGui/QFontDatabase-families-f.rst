.. sip:method-description::
    :status: todo
    :pysig: 13b1958f77fb77b6ca57d0dcd1e79572
    :realsig: (QFontDatabase::WritingSystem) const
    :digest: add200d039b0437fef211b02a3a96eb7

Returns a sorted list of the available font families which support the *writingSystem*.

If a family exists in several foundries, the returned name for that font is in the form "family [foundry]". Examples: "Times [Adobe]", "Times [Cronyx]", "Palatino".

.. seealso:: :sip:ref:`~PyQt5.QtGui.QFontDatabase.writingSystems`.
