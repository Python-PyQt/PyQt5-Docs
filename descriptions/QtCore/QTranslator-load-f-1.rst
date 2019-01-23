.. sip:method-description::
    :status: todo
    :pysig: 120a39240d53b7ec7fb3fc745d506820
    :realsig: (const QLocale&,const QString&,const QString&,const QString&,const QString&)
    :digest: 7cb09eb318ad684c09d7d10ead489101

Loads *filename* + *prefix* + :sip:ref:`~PyQt5.QtCore.QLocale.uiLanguages` + *suffix* (".qm" if the *suffix* is not specified), which may be an absolute file name or relative to *directory*. Returns ``true`` if the translation is successfully loaded; otherwise returns ``false``.

The previous contents of this translator object are discarded.

If the file name does not exist, other file names are tried in the following order:

#. File name without *suffix* appended.

#. File name with ui language part after a "_" character stripped and *suffix*.

#. File name with ui language part stripped without *suffix* appended.

#. File name with ui language part stripped further, etc.

For example, an application running in the *locale* with the following :sip:ref:`~PyQt5.QtCore.QLocale.uiLanguages` - "es", "fr-CA", "de" might call load(QLocale(), "foo", ".", "/opt/foolib", ".qm"). :sip:ref:`~PyQt5.QtCore.QTranslator.load` would replace '-' (dash) with '_' (underscore) in the ui language and then try to open the first existing readable file from this list:

#. ``/opt/foolib/foo.es.qm``

#. ``/opt/foolib/foo.es``

#. ``/opt/foolib/foo.fr_CA.qm``

#. ``/opt/foolib/foo.fr_CA``

#. ``/opt/foolib/foo.de.qm``

#. ``/opt/foolib/foo.de``

#. ``/opt/foolib/foo.fr.qm``

#. ``/opt/foolib/foo.fr``

#. ``/opt/foolib/foo.qm``

#. ``/opt/foolib/foo``.

#. ``/opt/foolib/foo``

On operating systems where file system is case sensitive, :sip:ref:`~PyQt5.QtCore.QTranslator` also tries to load a lower-cased version of the locale name.
