.. sip:class-description::
    :status: todo
    :brief: The base class for all PropertyValueAdded QSceneChange events
    :realname: Qt3DCore::QPropertyValueAddedChangeBase
    :digest: e52ee9ae14815f22a1c2436c242395c5

The :sip:ref:`~PyQt5.Qt3DCore.QPropertyValueAddedChangeBase` class is the base class for all :sip:ref:`~PyQt5.Qt3DCore.ChangeFlag.PropertyValueAdded` QSceneChange events.

The :sip:ref:`~PyQt5.Qt3DCore.QPropertyValueAddedChangeBase` class is the base class for all QSceneChange events that have the changeType() :sip:ref:`~PyQt5.Qt3DCore.ChangeFlag.PropertyValueAdded`. You should not need to instantiate this class. Usually you should be using one of its subclasses such as QPropertyNodeAddedChange.

You can subclass this to create your own node added types for communication between your QNode and QBackendNode subclasses when writing your own aspects.
