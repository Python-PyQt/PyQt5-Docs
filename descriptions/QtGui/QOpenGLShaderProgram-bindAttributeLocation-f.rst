.. sip:method-description::
    :status: todo
    :pysig: 808f4ef5f38799b92f91b87d7a1686ac
    :realsig: (const QByteArray&,int)
    :digest: 286562e3f26395b44a9f87908cd191c5

This is an overloaded function.

Binds the attribute *name* to the specified *location*. This function can be called before or after the program has been linked. Any attributes that have not been explicitly bound when the program is linked will be assigned locations automatically.

When this function is called after the program has been linked, the program will need to be relinked for the change to take effect.

.. seealso:: :sip:ref:`~PyQt5.QtGui.QOpenGLShaderProgram.attributeLocation`.
