.. sip:class-description::
    :status: todo
    :brief: Used to check a string against a regular expression
    :digest: c7388dba589846365fba4f1937d67110

The :sip:ref:`~PyQt5.QtGui.QRegExpValidator` class is used to check a string against a regular expression.

:sip:ref:`~PyQt5.QtGui.QRegExpValidator` uses a regular expression (regexp) to determine whether an input string is :sip:ref:`~PyQt5.QtGui.QValidator.State.Acceptable`, :sip:ref:`~PyQt5.QtGui.QValidator.State.Intermediate`, or :sip:ref:`~PyQt5.QtGui.QValidator.State.Invalid`. The regexp can either be supplied when the :sip:ref:`~PyQt5.QtGui.QRegExpValidator` is constructed, or at a later time.

When :sip:ref:`~PyQt5.QtGui.QRegExpValidator` determines whether a string is :sip:ref:`~PyQt5.QtGui.QValidator.State.Acceptable` or not, the regexp is treated as if it begins with the start of string assertion (\ **^**) and ends with the end of string assertion (\ **$**); the match is against the entire input string, or from the given position if a start position greater than zero is given.

If a string is a prefix of an :sip:ref:`~PyQt5.QtGui.QValidator.State.Acceptable` string, it is considered :sip:ref:`~PyQt5.QtGui.QValidator.State.Intermediate`. For example, "" and "A" are :sip:ref:`~PyQt5.QtGui.QValidator.State.Intermediate` for the regexp **[A-Z][0-9]** (whereas "_" would be :sip:ref:`~PyQt5.QtGui.QValidator.State.Invalid`).

For a brief introduction to Qt's regexp engine, see :sip:ref:`~PyQt5.QtCore.QRegExp`.

Example of use:

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-code-src_gui_util_qvalidator.py
    :lines: 106-111

Below we present some examples of validators. In practice they would normally be associated with a widget as in the example above.

.. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-code-src_gui_util_qvalidator.py
    :lines: 116-146

.. seealso:: :sip:ref:`~PyQt5.QtCore.QRegExp`, :sip:ref:`~PyQt5.QtGui.QIntValidator`, :sip:ref:`~PyQt5.QtGui.QDoubleValidator`, `Settings Editor Example <https://doc.qt.io/qt-5/qtwidgets-tools-settingseditor-example.html>`_.
