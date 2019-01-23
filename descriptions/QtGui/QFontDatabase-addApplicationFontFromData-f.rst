.. sip:method-description::
    :status: todo
    :pysig: 66933e733790e214c429279b11d28964
    :realsig: (const QByteArray&)
    :digest: 6975fc6e9b54cabeb72648e68c2bf91b

Loads the font from binary data specified by *fontData* and makes it available to the application. An ID is returned that can be used to remove the font again with :sip:ref:`~PyQt5.QtGui.QFontDatabase.removeApplicationFont` or to retrieve the list of family names contained in the font.

The function returns -1 if the font could not be loaded.

Currently only TrueType fonts and TrueType font collections are supported.

**Note:** Adding application fonts on Unix/X11 platforms without fontconfig is currently not supported.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QFontDatabase.addApplicationFont`, :sip:ref:`~PyQt5.QtGui.QFontDatabase.applicationFontFamilies`, :sip:ref:`~PyQt5.QtGui.QFontDatabase.removeApplicationFont`.
