.. sip:class-description::
    :status: todo
    :brief: Convenience class for drawing QStyle elements inside a widget
    :digest: 463505dd693cbc0da4cc78b392b8507d

The :sip:ref:`~PyQt5.QtWidgets.QStylePainter` class is a convenience class for drawing QStyle elements inside a widget.

:sip:ref:`~PyQt5.QtWidgets.QStylePainter` extends :sip:ref:`~PyQt5.QtGui.QPainter` with a set of high-level ``draw...()`` functions implemented on top of QStyle's API. The advantage of using :sip:ref:`~PyQt5.QtWidgets.QStylePainter` is that the parameter lists get considerably shorter. Whereas a QStyle object must be able to draw on any widget using any painter (because the application normally has one QStyle object shared by all widget), a :sip:ref:`~PyQt5.QtWidgets.QStylePainter` is initialized with a widget, eliminating the need to specify the :sip:ref:`~PyQt5.QtWidgets.QWidget`, the :sip:ref:`~PyQt5.QtGui.QPainter`, and the QStyle for every function call.

Example using QStyle directly:

.. literalinclude:: ../../../snippets/qtbase-src-widgets-doc-snippets-styles-styles.py
    :lines: 66-80

Example using :sip:ref:`~PyQt5.QtWidgets.QStylePainter`:

.. literalinclude:: ../../../snippets/qtbase-src-widgets-doc-snippets-styles-styles.py
    :lines: 66-66

.. literalinclude:: ../../../snippets/qtbase-src-widgets-doc-snippets-styles-styles.py
    :lines: 85-85

.. literalinclude:: ../../../snippets/qtbase-src-widgets-doc-snippets-styles-styles.py
    :lines: 87-97

.. seealso:: QStyleQStyleOption.
