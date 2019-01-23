.. sip:class-description::
    :status: todo
    :brief: The base class for all NodeCreated QSceneChange events
    :realname: Qt3DCore::QNodeCreatedChangeBase
    :digest: c32c0134bf09c2688b60a0c691ac3f4b

The :sip:ref:`~PyQt5.Qt3DCore.QNodeCreatedChangeBase` class is the base class for all :sip:ref:`~PyQt5.Qt3DCore.ChangeFlag.NodeCreated` QSceneChange events.

The :sip:ref:`~PyQt5.Qt3DCore.QNodeCreatedChangeBase` class is the base class for all QSceneChange events that have the changeType() :sip:ref:`~PyQt5.Qt3DCore.ChangeFlag.NodeCreated`. You should not need to instantiate this class. Usually you should be using one of its subclasses such as QNodeCreatedChange.

You can subclass this to create your own node update types for communication between your QNode and QBackendNode subclasses when writing your own aspects.
