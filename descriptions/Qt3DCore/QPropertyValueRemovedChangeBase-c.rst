.. sip:class-description::
    :status: todo
    :brief: The base class for all PropertyValueRemoved QSceneChange events
    :realname: Qt3DCore::QPropertyValueRemovedChangeBase
    :digest: 63f43d2130d46326d3ba2ffd965d6808

The :sip:ref:`~PyQt5.Qt3DCore.QPropertyValueRemovedChangeBase` class is the base class for all :sip:ref:`~PyQt5.Qt3DCore.ChangeFlag.PropertyValueRemoved` QSceneChange events.

The :sip:ref:`~PyQt5.Qt3DCore.QPropertyValueRemovedChangeBase` class is the base class for all QSceneChange events that have the changeType() :sip:ref:`~PyQt5.Qt3DCore.ChangeFlag.PropertyValueRemoved`. You should not need to instantiate this class. Usually you should be using one of its subclasses such as QPropertyNodeRemovedChange.

You can subclass this to create your own node Removed types for communication between your QNode and QBackendNode subclasses when writing your own aspects.
