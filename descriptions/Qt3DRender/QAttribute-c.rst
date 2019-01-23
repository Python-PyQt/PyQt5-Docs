.. sip:class-description::
    :status: todo
    :brief: Defines an attribute and how data should be read from a QBuffer
    :realname: Qt3DRender::QAttribute
    :digest: d9913e3119174b122cffe596a7bb717e

Defines an attribute and how data should be read from a :sip:ref:`~PyQt5.QtCore.QBuffer`.

There are 3 types of attributes.

* :sip:ref:`~PyQt5.Qt3DRender.QAttribute.AttributeType.VertexAttribute`: used to define data to be read on a per vertex basis

* :sip:ref:`~PyQt5.Qt3DRender.QAttribute.AttributeType.IndexAttribute`: used to define vertex indices when indexed draw calls are to be used

* :sip:ref:`~PyQt5.Qt3DRender.QAttribute.AttributeType.DrawIndirectAttribute`: used to specify the DrawIndirect buffer to be used when indirect draw calls are to be used

**Note:** when an attribute is of type :sip:ref:`~PyQt5.Qt3DRender.QAttribute.AttributeType.DrawIndirectAttribute`, only count, stride and offset are relevant.

When providing your own attributes, it may make sense to name your attribute using helpers such as QAttribute::defaultPositionAttributeName() as that will ensure your geometry will be compatible with picking and the various materials provided in the :sip:ref:`~PyQt5.Qt3DExtras.Qt3DExtras` module.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QBuffer`.
