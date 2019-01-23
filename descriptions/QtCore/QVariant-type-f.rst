.. sip:method-description::
    :status: todo
    :pysig: 7315aa43ae06953fab9deb476d0950e4
    :realsig: () const
    :digest: f8290608072887f43fc1623d01a9799e

Returns the storage type of the value stored in the variant. Although this function is declared as returning :sip:ref:`~PyQt5.QtCore.QVariant.Type`, the return value should be interpreted as :sip:ref:`~PyQt5.QtCore.QMetaType.Type`. In particular, :sip:ref:`~PyQt5.QtCore.QVariant.Type.UserType` is returned here only if the value is equal or greater than :sip:ref:`~PyQt5.QtCore.QMetaType.Type.User`.

Note that return values in the ranges :sip:ref:`~PyQt5.QtCore.QVariant.Type.Char` through :sip:ref:`~PyQt5.QtCore.QVariant.Type.RegExp` and :sip:ref:`~PyQt5.QtCore.QVariant.Type.Font` through :sip:ref:`~PyQt5.QtCore.QVariant.Type.Transform` correspond to the values in the ranges :sip:ref:`~PyQt5.QtCore.QMetaType.Type.QChar` through :sip:ref:`~PyQt5.QtCore.QMetaType.Type.QRegExp` and :sip:ref:`~PyQt5.QtCore.QMetaType.Type.QFont` through :sip:ref:`~PyQt5.QtCore.QMetaType.Type.QQuaternion`.

Pay particular attention when working with char and QChar variants. Note that there is no :sip:ref:`~PyQt5.QtCore.QVariant` constructor specifically for type char, but there is one for QChar. For a variant of type QChar, this function returns :sip:ref:`~PyQt5.QtCore.QVariant.Type.Char`, which is the same as :sip:ref:`~PyQt5.QtCore.QMetaType.Type.QChar`, but for a variant of type ``char``, this function returns :sip:ref:`~PyQt5.QtCore.QMetaType.Type.Char`, which is *not* the same as :sip:ref:`~PyQt5.QtCore.QVariant.Type.Char`.

Also note that the types ``void\*``, ``long``, ``short``, ``unsigned`` ``long``, ``unsigned`` ``short``, ``unsigned`` ``char``, ``float``, ``QObject\*``, and ``QWidget\*`` are represented in :sip:ref:`~PyQt5.QtCore.QMetaType.Type` but not in :sip:ref:`~PyQt5.QtCore.QVariant.Type`, and they can be returned by this function. However, they are considered to be user defined types when tested against :sip:ref:`~PyQt5.QtCore.QVariant.Type`.

To test whether an instance of :sip:ref:`~PyQt5.QtCore.QVariant` contains a data type that is compatible with the data type you are interested in, use :sip:ref:`~PyQt5.QtCore.QVariant.canConvert`.
