.. sip:method-description::
    :status: todo
    :pysig: 2444386b61608a55a9a51e143ee00e3f
    :realsig: (QTranslator*)
    :digest: 9d6c7d7ca5d1bc94203692c05df9b140

Removes the translation file *translationFile* from the list of translation files used by this application. (It does not delete the translation file from the file system.)

The function returns ``true`` on success and false on failure.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QCoreApplication.installTranslator`, :sip:ref:`~PyQt5.QtCore.QCoreApplication.translate`, :sip:ref:`~PyQt5.QtCore.QObject.tr`.
