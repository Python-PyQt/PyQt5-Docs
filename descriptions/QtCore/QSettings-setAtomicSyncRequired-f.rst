.. sip:method-description::
    :status: todo
    :pysig: c506ff134babdd6e68ab3e6350e95305
    :realsig: (bool)
    :digest: f4ce0bf2462576d277f8ce7eaf20621c

Configures whether :sip:ref:`~PyQt5.QtCore.QSettings` is required to perform atomic saving and reloading (synchronization) of the settings. If the *enable* argument is ``true`` (the default), :sip:ref:`~PyQt5.QtCore.QSettings.sync` will only perform synchronization operations that are atomic. If this is not possible, :sip:ref:`~PyQt5.QtCore.QSettings.sync` will fail and :sip:ref:`~PyQt5.QtCore.QSettings.status` will be an error condition.

Setting this property to ``false`` will allow :sip:ref:`~PyQt5.QtCore.QSettings` to write directly to the configuration file and ignore any errors trying to lock it against other processes trying to write at the same time. Because of the potential for corruption, this option should be used with care, but is required in certain conditions, like a QSettings::IniFormat configuration file that exists in an otherwise non-writeable directory or NTFS Alternate Data Streams.

See :sip:ref:`~PyQt5.QtCore.QSaveFile` for more information on the feature.

.. seealso:: :sip:ref:`~PyQt5.QtCore.QSettings.isAtomicSyncRequired`, :sip:ref:`~PyQt5.QtCore.QSaveFile`.
