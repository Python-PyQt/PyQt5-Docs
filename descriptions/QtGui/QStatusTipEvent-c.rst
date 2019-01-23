.. sip:class-description::
    :status: todo
    :brief: Event that is used to show messages in a status bar
    :digest: 86a220b9a58da02998b9ec22e6b18211

The :sip:ref:`~PyQt5.QtGui.QStatusTipEvent` class provides an event that is used to show messages in a status bar.

Status tips can be set on a widget using the QWidget::setStatusTip() function. They are shown in the status bar when the mouse cursor enters the widget. For example:

+-------------------------------------------------------------------------------------------+-------------------------------------------------------+
| .. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-qstatustipevent-main.py | .. image:: ../../../images/qstatustipevent-widget.png |
|     :lines: 63-70                                                                         |                                                       |
|                                                                                           |                                                       |
| .. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-qstatustipevent-main.py |                                                       |
|     :lines: 84-84                                                                         |                                                       |
+-------------------------------------------------------------------------------------------+-------------------------------------------------------+

Status tips can also be set on actions using the QAction::setStatusTip() function:

+-------------------------------------------------------------------------------------------+-------------------------------------------------------+
| .. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-qstatustipevent-main.py | .. image:: ../../../images/qstatustipevent-action.png |
|     :lines: 63-65                                                                         |                                                       |
|                                                                                           |                                                       |
| .. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-qstatustipevent-main.py |                                                       |
|     :lines: 74-78                                                                         |                                                       |
|                                                                                           |                                                       |
| .. literalinclude:: ../../../snippets/qtbase-src-gui-doc-snippets-qstatustipevent-main.py |                                                       |
|     :lines: 84-84                                                                         |                                                       |
+-------------------------------------------------------------------------------------------+-------------------------------------------------------+

Finally, status tips are supported for the item view classes through the :sip:ref:`~PyQt5.QtCore.Qt.ItemDataRole.StatusTipRole` enum value.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QHelpEvent`, :sip:ref:`~PyQt5.QtGui.QWhatsThisClickedEvent`, :sip:ref:`~PyQt5.QtWidgets.QStatusBar`.
