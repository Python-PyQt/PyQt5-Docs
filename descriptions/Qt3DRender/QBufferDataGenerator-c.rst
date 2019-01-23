.. sip:class-description::
    :status: todo
    :brief: Provides a mechanism to generate buffer data from a job
    :realname: Qt3DRender::QBufferDataGenerator
    :digest: dac5607fbe4ddb828e4b473ba82554c4

Provides a mechanism to generate buffer data from a job.

The :sip:ref:`~PyQt5.Qt3DRender.QBufferDataGenerator` should be subclassed to provide a way to fill the data of a :sip:ref:`~PyQt5.Qt3DRender.QBuffer`. Such functors are executed at runtime in a Qt 3D job (likely in parallel with many other jobs). When providing a functor you must implement the operator() which will be called to generate the actual data. You must make sure that you have stored copies of anything you might need for it to execute properly. You should also implement the operator==. It will be used to compare with other functors and based on that allow the renderer to decide if a new functor should be executed or not.

**Note:** functors are useful when you can build data from a few set of attributes (e.g: building a sphere from a radius property). If you already have access to the buffer data, using Qt3DRender::QBuffer::setData() is likely more efficient.

::

    QByteArray createSphereMeshVertexData(float radius, int rings, int slices)
    {
        ...
    }

    class SphereVertexDataFunctor : public QBufferDataGenerator
    {
    public:
        SphereVertexDataFunctor(int rings, int slices, float radius)
            : m_rings(rings)
            , m_slices(slices)
            , m_radius(radius)
        {}

        QByteArray operator ()() override
        {
            return createSphereMeshVertexData(m_radius, m_rings, m_slices);
        }

        bool operator ==(const QBufferDataGenerator &other) const override
        {
            const SphereVertexDataFunctor *otherFunctor = functor_cast<SphereVertexDataFunctor>(&other);
            if (otherFunctor != nullptr)
                return (otherFunctor->m_rings == m_rings &&
                        otherFunctor->m_slices == m_slices &&
                        otherFunctor->m_radius == m_radius);
            return false;
        }

        QT3D_FUNCTOR(SphereVertexDataFunctor)

    private:
        int m_rings;
        int m_slices;
        float m_radius;
    };

The QT3D_FUNCTOR macro should be added when subclassing. This allows you to use functor_cast in your comparison operator to make sure that the other functor is of the same type as the one your are trying to compare against.
