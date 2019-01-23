.. sip:class-description::
    :status: todo
    :brief: Provides a data store for raw data to later be used as vertices or uniforms
    :realname: Qt3DRender::QBuffer
    :digest: b770190243201d0aee56d7604ee12842

Provides a data store for raw data to later be used as vertices or uniforms.

Data can either be provided directly using :sip:ref:`~PyQt5.QtCore.QBuffer.setData` or by specifying a generator with QBuffer::setDataGenerator() and providing a Qt3DRender::QBufferDataGeneratorPtr.

When using a generator the data will be loaded asynchronously in a job. The loaded data can be read back if the QBuffer::syncData flag is set to true.
