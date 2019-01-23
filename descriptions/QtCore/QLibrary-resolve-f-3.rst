.. sip:method-description::
    :status: todo
    :pysig: 7537c98cab057e361f3ce0036b3a76f3
    :realsig: (const QString&,const QString&,const char*)
    :digest: f296ce5a13f2961e4aaf65ab2ed9231f

This is an overloaded function.

Loads the library *fileName* with full version number *version* and returns the address of the exported symbol *symbol*. Note that *fileName* should not include the platform-specific file suffix; (see :sip:ref:`~PyQt5.QtCore.QLibrary.fileName`). The library remains loaded until the application exits. *version* is ignored on Windows.

The function returns 0 if the symbol could not be resolved or if the library could not be loaded.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QLibrary.resolve`.
