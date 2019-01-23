.. sip:method-description::
    :status: todo
    :pysig: f3c1ea8cdc226f1c6d1536b6891b19f7
    :realsig: (QObject*)
    :digest: 7baa0612860a88f9c7fcf394e0fd4eb6

Constructs an object with parent object *parent*.

The parent of an object may be viewed as the object's owner. For instance, a dialog box is the parent of the OK and Cancel buttons it contains.

The destructor of a parent object destroys all child objects.

Setting *parent* to 0 constructs an object with no parent. If the object is a widget, it will become a top-level window.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QObject.parent`, :sip:ref:`~PyQt5.QtCore.QObject.findChild`, :sip:ref:`~PyQt5.QtCore.QObject.findChildren`.
