.. sip:method-description::
    :status: todo
    :pysig: 87154c9a9a845489fbfb99cee1eb3348
    :realname: Qt3DCore::QNode::notifyObservers
    :realsig: (const Qt3DCore::QSceneChangePtr&)
    :digest: fe7e3dee6d425b37c1e563139374047a

Sends the *change* QSceneChangePtr to any QBackendNodes in the registered aspects that correspond to this :sip:ref:`~PyQt5.Qt3DCore.QNode`.

For the common case of a :sip:ref:`~PyQt5.QtCore.QObject` property change, :sip:ref:`~PyQt5.Qt3DCore.QNode` handles this for you automatically by sending a QPropertyUpdatedChange event to the backend nodes. You only need to call this function if you wish to send a specific type of change in place of the automatic handling.
