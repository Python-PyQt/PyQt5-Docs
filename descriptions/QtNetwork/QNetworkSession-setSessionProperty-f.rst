.. sip:method-description::
    :status: todo
    :pysig: 9064598f6881fe97156ec2e9c47c55cf
    :realsig: (const QString&,const QVariant&)
    :digest: 0d5721233c3fc4155974339e89acad33

Sets the property *value* on the session. The property is identified using *key*. Removing an already set property can be achieved by passing an invalid :sip:ref:`~PyQt5.QtCore.QVariant`.

Note that the *UserChoiceConfiguration* and *ActiveConfiguration* properties are read only and cannot be changed using this method.

.. seealso:: :sip:ref:`~PyQt5.QtNetwork.QNetworkSession.sessionProperty`.
