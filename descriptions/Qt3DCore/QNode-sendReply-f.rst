.. sip:method-description::
    :status: todo
    :pysig: 112028e6c6b43b62b273db7eaf26c2a4
    :realname: Qt3DCore::QNode::sendReply
    :realsig: (const Qt3DCore::QNodeCommandPtr&)
    :digest: a3507cd4d3815acd4aae2c9988901955

Send a *command* back to the backend node.

Assumes the command is to be to sent back in reply to itself to the backend node.

.. seealso:: QNodeCommand, QNode::sendCommand.
