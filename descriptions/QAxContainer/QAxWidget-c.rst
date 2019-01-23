.. sip:class-description::
    :status: todo
    :brief: QWidget that wraps an ActiveX control
    :digest: bc7015992f00e0daba5afcba721f773d

The :sip:ref:`~PyQt5.QAxContainer.QAxWidget` class is a :sip:ref:`~PyQt5.QtWidgets.QWidget` that wraps an ActiveX control.

A :sip:ref:`~PyQt5.QAxContainer.QAxWidget` can be instantiated as an empty object, with the name of the ActiveX control it should wrap, or with an existing interface pointer to the ActiveX control. The ActiveX control's properties, methods and events which only use QAxBase supported data types, become available as Qt properties, slots and signals. The base class QAxBase provides an API to access the ActiveX directly through the ``IUnknown`` pointer.

:sip:ref:`~PyQt5.QAxContainer.QAxWidget` is a :sip:ref:`~PyQt5.QtWidgets.QWidget` and can mostly be used as such, e.g. it can be organized in a widget hierarchy and layouts or act as an event filter. Standard widget properties, e.g. enabled are supported, but it depends on the ActiveX control to implement support for ambient properties like e.g. palette or font. :sip:ref:`~PyQt5.QAxContainer.QAxWidget` tries to provide the necessary hints.

However, you cannot reimplement Qt-specific event handlers like mousePressEvent or keyPressEvent and expect them to be called reliably. The embedded control covers the :sip:ref:`~PyQt5.QAxContainer.QAxWidget` completely, and usually handles the user interface itself. Use control-specific APIs (i.e. listen to the signals of the control), or use standard COM techniques like window procedure subclassing.

:sip:ref:`~PyQt5.QAxContainer.QAxWidget` also inherits most of its ActiveX-related functionality from QAxBase, notably dynamicCall() and querySubObject().

**Warning:** You can subclass :sip:ref:`~PyQt5.QAxContainer.QAxWidget`, but you cannot use the ``Q_OBJECT`` macro in the subclass (the generated moc-file will not compile), so you cannot add further signals, slots or properties. This limitation is due to the metaobject information generated in runtime. To work around this problem, aggregate the :sip:ref:`~PyQt5.QAxContainer.QAxWidget` as a member of the :sip:ref:`~PyQt5.QtCore.QObject` subclass.

.. seealso:: QAxScript, `ActiveQt Framework <https://doc.qt.io/qt-5/activeqt-index.html>`_, QAxBaseQAxObject.
