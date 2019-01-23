.. sip:method-description::
    :status: todo
    :pysig: 8b8f8b4a0f012d2f90c3e2fdcfe7c3a1
    :realname: Qt3DCore::QEntity::parentEntity
    :realsig: () const
    :digest: f0da8f070d7e287866f489481e6e342a

Returns the parent :sip:ref:`~PyQt5.Qt3DCore.QEntity` instance of this entity. If the immediate parent isn't a :sip:ref:`~PyQt5.Qt3DCore.QEntity`, this function traverses up the scene hierarchy until a parent :sip:ref:`~PyQt5.Qt3DCore.QEntity` is found. If no :sip:ref:`~PyQt5.Qt3DCore.QEntity` parent can be found, returns null.
