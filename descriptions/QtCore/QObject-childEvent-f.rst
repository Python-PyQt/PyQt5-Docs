.. sip:method-description::
    :status: todo
    :pysig: 85240722cfe59edd580437f27f7a6dfd
    :realsig: (QChildEvent*)
    :digest: 69663a28a61770a0b539170e231b60e2

This event handler can be reimplemented in a subclass to receive child events. The event is passed in the *event* parameter.

:sip:ref:`~PyQt5.QtCore.QEvent.Type.ChildAdded` and :sip:ref:`~PyQt5.QtCore.QEvent.Type.ChildRemoved` events are sent to objects when children are added or removed. In both cases you can only rely on the child being a :sip:ref:`~PyQt5.QtCore.QObject`, or if :sip:ref:`~PyQt5.QtCore.QObject.isWidgetType` returns ``true``, a :sip:ref:`~PyQt5.QtWidgets.QWidget`. (This is because, in the :sip:ref:`~PyQt5.QtCore.QEvent.Type.ChildAdded` case, the child is not yet fully constructed, and in the :sip:ref:`~PyQt5.QtCore.QEvent.Type.ChildRemoved` case it might have been destructed already).

:sip:ref:`~PyQt5.QtCore.QEvent.Type.ChildPolished` events are sent to widgets when children are polished, or when polished children are added. If you receive a child polished event, the child's construction is usually completed. However, this is not guaranteed, and multiple polish events may be delivered during the execution of a widget's constructor.

For every child widget, you receive one :sip:ref:`~PyQt5.QtCore.QEvent.Type.ChildAdded` event, zero or more :sip:ref:`~PyQt5.QtCore.QEvent.Type.ChildPolished` events, and one :sip:ref:`~PyQt5.QtCore.QEvent.Type.ChildRemoved` event.

The :sip:ref:`~PyQt5.QtCore.QEvent.Type.ChildPolished` event is omitted if a child is removed immediately after it is added. If a child is polished several times during construction and destruction, you may receive several child polished events for the same child, each time with a different virtual table.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QObject.event`.
