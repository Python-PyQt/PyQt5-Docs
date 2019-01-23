.. sip:method-description::
    :status: todo
    :pysig: bd761508ae6ab2f2a2cac9a2a3296bc4
    :realsig: (const QString&,int,const char*)
    :digest: dc68d91e5fa4a669d4de1253e5490f64

This is an overloaded function.

Loads the library *fileName* with major version number *verNum* and returns the address of the exported symbol *symbol*. Note that *fileName* should not include the platform-specific file suffix; (see :sip:ref:`~PyQt5.QtCore.QLibrary.fileName`). The library remains loaded until the application exits. *verNum* is ignored on Windows.

The function returns 0 if the symbol could not be resolved or if the library could not be loaded.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QLibrary.resolve`.
