.. sip:class-description::
    :status: todo
    :brief: The base class for all PropertyUpdated QSceneChange events
    :realname: Qt3DCore::QPropertyUpdatedChangeBase
    :digest: dbcf6dc16737eba89af4b4527cdf8eeb

The :sip:ref:`~PyQt5.Qt3DCore.QPropertyUpdatedChangeBase` class is the base class for all :sip:ref:`~PyQt5.Qt3DCore.ChangeFlag.PropertyUpdated` QSceneChange events.

The :sip:ref:`~PyQt5.Qt3DCore.QPropertyUpdatedChangeBase` class is the base class for all QSceneChange events that have the changeType() :sip:ref:`~PyQt5.Qt3DCore.ChangeFlag.PropertyUpdated`. You should not need to instantiate this class. Usually you should be using one of its subclasses such as QPropertyUpdatedChange or QTypedPropertyUpdatedChange.

You can subclass this to create your own node update types for communication between your QNode and QBackendNode subclasses when writing your own aspects.
