.. sip:method-description::
    :status: todo
    :pysig: ed36a1ef76a59ee3f15180e0441188ad
    :realsig: () const
    :digest: 098b80e38435c614293047079dbb8a54

Converts the value to a :sip:ref:`~PyQt5.QtCore.QVariant.__init__`.

The :sip:ref:`~PyQt5.QtCore.QJsonValue` types will be converted as follows:

+-----------+------------------------------------------------+
| Constant  | Description                                    |
+===========+================================================+
| Null      | QMetaType::Nullptr                             |
+-----------+------------------------------------------------+
| Bool      | :sip:ref:`~PyQt5.QtCore.QMetaType.Type.Bool`   |
+-----------+------------------------------------------------+
| Double    | :sip:ref:`~PyQt5.QtCore.QMetaType.Type.Double` |
+-----------+------------------------------------------------+
| String    | QString                                        |
+-----------+------------------------------------------------+
| Array     | QVariantList                                   |
+-----------+------------------------------------------------+
| Object    | QVariantMap                                    |
+-----------+------------------------------------------------+
| Undefined | :sip:ref:`~PyQt5.QtCore.QVariant.__init__`     |
+-----------+------------------------------------------------+

.. seealso:: :sip:ref:`~PyQt5.QtCore.QJsonValue.fromVariant`.
