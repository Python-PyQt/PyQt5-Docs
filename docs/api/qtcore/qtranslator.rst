:orphan:

.. sip:class:: PyQt5.QtCore.QTranslator
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtCore/QTranslator-c.rst

    .. sip:method:: PyQt5.QtCore.QTranslator.__init__
        :args:
            parent: :sip:ref:`~PyQt5.QtCore.QObject` = None
        :description: QtCore/QTranslator-__init__-f.rst

    .. sip:method:: PyQt5.QtCore.QTranslator.filePath
        :returns:
            str
        :description: QtCore/QTranslator-filePath-f.rst

    .. sip:method:: PyQt5.QtCore.QTranslator.isEmpty
        :returns:
            bool
        :description: QtCore/QTranslator-isEmpty-f.rst

    .. sip:method:: PyQt5.QtCore.QTranslator.language
        :returns:
            str
        :description: QtCore/QTranslator-language-f.rst

    .. sip:method:: PyQt5.QtCore.QTranslator.load
        :args:
            str
            directory: str = ''
            searchDelimiters: str = ''
            suffix: str = ''
        :returns:
            bool
        :description: QtCore/QTranslator-load-f.rst

    .. sip:method:: PyQt5.QtCore.QTranslator.load
        :args:
            :sip:ref:`~PyQt5.QtCore.QLocale`
            str
            prefix: str = ''
            directory: str = ''
            suffix: str = ''
        :returns:
            bool
        :description: QtCore/QTranslator-load-f-1.rst

    .. sip:method:: PyQt5.QtCore.QTranslator.loadFromData
        :args:
            bytes
            directory: str = ''
        :returns:
            bool
        :description: QtCore/QTranslator-loadFromData-f.rst

    .. sip:method:: PyQt5.QtCore.QTranslator.translate
        :args:
            str
            str
            disambiguation: str = None
            n: int = -1
        :returns:
            str
        :description: QtCore/QTranslator-translate-f.rst
