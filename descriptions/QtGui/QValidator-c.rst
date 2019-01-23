.. sip:class-description::
    :status: todo
    :brief: Validation of input text
    :digest: 0f84b3a5b34bc6ca22959fb581040b1e

The :sip:ref:`~PyQt5.QtGui.QValidator` class provides validation of input text.

The class itself is abstract. Two subclasses, :sip:ref:`~PyQt5.QtGui.QIntValidator` and :sip:ref:`~PyQt5.QtGui.QDoubleValidator`, provide basic numeric-range checking, and :sip:ref:`~PyQt5.QtGui.QRegExpValidator` provides general checking using a custom regular expression.

If the built-in validators aren't sufficient, you can subclass :sip:ref:`~PyQt5.QtGui.QValidator`. The class has two virtual functions: :sip:ref:`~PyQt5.QtGui.QValidator.validate` and :sip:ref:`~PyQt5.QtGui.QValidator.fixup`.

:sip:ref:`~PyQt5.QtGui.QValidator.validate` must be implemented by every subclass. It returns :sip:ref:`~PyQt5.QtGui.QValidator.State.Invalid`, :sip:ref:`~PyQt5.QtGui.QValidator.State.Intermediate` or :sip:ref:`~PyQt5.QtGui.QValidator.State.Acceptable` depending on whether its argument is valid (for the subclass's definition of valid).

These three states require some explanation. An :sip:ref:`~PyQt5.QtGui.QValidator.State.Invalid` string is *clearly* invalid. :sip:ref:`~PyQt5.QtGui.QValidator.State.Intermediate` is less obvious: the concept of validity is difficult to apply when the string is incomplete (still being edited). :sip:ref:`~PyQt5.QtGui.QValidator` defines :sip:ref:`~PyQt5.QtGui.QValidator.State.Intermediate` as the property of a string that is neither clearly invalid nor acceptable as a final result. :sip:ref:`~PyQt5.QtGui.QValidator.State.Acceptable` means that the string is acceptable as a final result. One might say that any string that is a plausible intermediate state during entry of an :sip:ref:`~PyQt5.QtGui.QValidator.State.Acceptable` string is :sip:ref:`~PyQt5.QtGui.QValidator.State.Intermediate`.

Here are some examples:

* For a line edit that accepts integers from 10 to 1000 inclusive, 42 and 123 are :sip:ref:`~PyQt5.QtGui.QValidator.State.Acceptable`, the empty string and 5 are :sip:ref:`~PyQt5.QtGui.QValidator.State.Intermediate`, and "asdf" and 1114 is :sip:ref:`~PyQt5.QtGui.QValidator.State.Invalid`.

* For an editable combobox that accepts URLs, any well-formed URL is :sip:ref:`~PyQt5.QtGui.QValidator.State.Acceptable`, "http://example.com/," is :sip:ref:`~PyQt5.QtGui.QValidator.State.Intermediate` (it might be a cut and paste action that accidentally took in a comma at the end), the empty string is :sip:ref:`~PyQt5.QtGui.QValidator.State.Intermediate` (the user might select and delete all of the text in preparation for entering a new URL) and "http:///./" is :sip:ref:`~PyQt5.QtGui.QValidator.State.Invalid`.

* For a spin box that accepts lengths, "11cm" and "1in" are :sip:ref:`~PyQt5.QtGui.QValidator.State.Acceptable`, "11" and the empty string are :sip:ref:`~PyQt5.QtGui.QValidator.State.Intermediate`, and "http://example.com" and "hour" are :sip:ref:`~PyQt5.QtGui.QValidator.State.Invalid`.

:sip:ref:`~PyQt5.QtGui.QValidator.fixup` is provided for validators that can repair some user errors. The default implementation does nothing. QLineEdit, for example, will call :sip:ref:`~PyQt5.QtGui.QValidator.fixup` if the user presses Enter (or Return) and the content is not currently valid. This allows the :sip:ref:`~PyQt5.QtGui.QValidator.fixup` function the opportunity of performing some magic to make an :sip:ref:`~PyQt5.QtGui.QValidator.State.Invalid` string :sip:ref:`~PyQt5.QtGui.QValidator.State.Acceptable`.

A validator has a locale, set with :sip:ref:`~PyQt5.QtGui.QValidator.setLocale`. It is typically used to parse localized data. For example, :sip:ref:`~PyQt5.QtGui.QIntValidator` and :sip:ref:`~PyQt5.QtGui.QDoubleValidator` use it to parse localized representations of integers and doubles.

:sip:ref:`~PyQt5.QtGui.QValidator` is typically used with QLineEdit, QSpinBox and QComboBox.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QIntValidator`, :sip:ref:`~PyQt5.QtGui.QDoubleValidator`, :sip:ref:`~PyQt5.QtGui.QRegExpValidator`, `Line Edits Example <https://doc.qt.io/qt-5/qtwidgets-widgets-lineedits-example.html>`_.
