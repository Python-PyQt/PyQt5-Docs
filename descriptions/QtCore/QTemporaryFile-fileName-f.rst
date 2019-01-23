.. sip:method-description::
    :status: todo
    :pysig: 341be97d9aff90c9978347f66f945b77
    :realsig: () const
    :digest: bf8b5e7bf349c88c2345c15a3ef052d0

Returns the complete unique filename backing the :sip:ref:`~PyQt5.QtCore.QTemporaryFile` object. This string is null before the :sip:ref:`~PyQt5.QtCore.QTemporaryFile` is opened, afterwards it will contain the :sip:ref:`~PyQt5.QtCore.QTemporaryFile.fileTemplate` plus additional characters to make it unique.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QTemporaryFile.fileTemplate`.
