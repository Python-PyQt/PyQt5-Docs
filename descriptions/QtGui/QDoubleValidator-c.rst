.. sip:class-description::
    :status: todo
    :brief: Range checking of floating-point numbers
    :digest: 91103cb124d0de86d65abf22f769f52d

The :sip:ref:`~PyQt5.QtGui.QDoubleValidator` class provides range checking of floating-point numbers.

:sip:ref:`~PyQt5.QtGui.QDoubleValidator` provides an upper bound, a lower bound, and a limit on the number of digits after the decimal point. It does not provide a fixup() function.

You can set the acceptable range in one call with :sip:ref:`~PyQt5.QtGui.QDoubleValidator.setRange`, or with :sip:ref:`~PyQt5.QtGui.QDoubleValidator.setBottom` and :sip:ref:`~PyQt5.QtGui.QDoubleValidator.setTop`. Set the number of decimal places with :sip:ref:`~PyQt5.QtGui.QDoubleValidator.setDecimals`. The :sip:ref:`~PyQt5.QtGui.QDoubleValidator.validate` function returns the validation state.

:sip:ref:`~PyQt5.QtGui.QDoubleValidator` uses its locale() to interpret the number. For example, in the German locale, "1,234" will be accepted as the fractional number 1.234. In Arabic locales, :sip:ref:`~PyQt5.QtGui.QDoubleValidator` will accept Arabic digits.

**Note:** The QLocale::NumberOptions set on the locale() also affect the way the number is interpreted. For example, since :sip:ref:`~PyQt5.QtCore.QLocale.NumberOption.RejectGroupSeparator` is not set by default, the validator will accept group separators. It is thus recommended to use :sip:ref:`~PyQt5.QtCore.QLocale.toDouble` to obtain the numeric value.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QIntValidator`, :sip:ref:`~PyQt5.QtGui.QRegExpValidator`, :sip:ref:`~PyQt5.QtCore.QLocale.toDouble`, `Line Edits Example <https://doc.qt.io/qt-5/qtwidgets-widgets-lineedits-example.html>`_.
