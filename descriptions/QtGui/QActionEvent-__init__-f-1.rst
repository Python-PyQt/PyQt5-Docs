.. sip:method-description::
    :status: todo
    :pysig: c156f4e1e49285b35afe698866105daf
    :realsig: (int,QAction*,QAction*)
    :digest: 8c83eb034d18107876d773210a651fb2

Constructs an action event. The *type* can be :sip:ref:`~PyQt5.QtCore.QEvent.Type.ActionChanged`, :sip:ref:`~PyQt5.QtCore.QEvent.Type.ActionAdded`, or :sip:ref:`~PyQt5.QtCore.QEvent.Type.ActionRemoved`.

*action* is the action that is changed, added, or removed. If *type* is :sip:ref:`~PyQt5.QtCore.QEvent.Type.ActionAdded`, the action is to be inserted before the action *before*. If *before* is 0, the action is appended.
