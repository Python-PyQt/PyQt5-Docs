.. sip:method-description::
    :status: todo
    :pysig: 341be97d9aff90c9978347f66f945b77
    :realsig: (const QString&)
    :digest: 84c1e4abb4e7f9d1f392353ba13126ad

Constructs a :sip:ref:`~PyQt5.QtCore.QLocale` object with the specified *name*, which has the format "language[_script][_country][.codeset][@modifier]" or "C", where:

* language is a lowercase, two-letter, ISO 639 language code (also some three-letter codes),

* script is a titlecase, four-letter, ISO 15924 script code,

* country is an uppercase, two-letter, ISO 3166 country code (also "419" as defined by United Nations),

* and codeset and modifier are ignored.

The separator can be either underscore or a minus sign.

If the string violates the locale format, or language is not a valid ISO 639 code, the "C" locale is used instead. If country is not present, or is not a valid ISO 3166 code, the most appropriate country is chosen for the specified language.

The language, script and country codes are converted to their respective ``Language``, ``Script`` and ``Country`` enums. After this conversion is performed, the constructor behaves exactly like :sip:ref:`~PyQt5.QtCore.QLocale`\ (Country, Script, Language).

This constructor is much slower than :sip:ref:`~PyQt5.QtCore.QLocale`\ (Country, Script, Language).

.. seealso:: :sip:ref:`~PyQt5.QtCore.QLocale.bcp47Name`.
