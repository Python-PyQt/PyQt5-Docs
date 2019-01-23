:orphan:

.. sip:class:: PyQt5.QtQml.QJSEngine
    :inherits: :sip:ref:`~PyQt5.QtCore.QObject`
    :description: QtQml/QJSEngine-c.rst

    .. sip:enum:: PyQt5.QtQml.QJSEngine.Extension
        :description: QtQml/QJSEngine-Extension-e.rst

        .. sip:enum-member:: PyQt5.QtQml.QJSEngine.Extension.AllExtensions
            :description: QtQml/QJSEngine-Extension-AllExtensions-v.rst

        .. sip:enum-member:: PyQt5.QtQml.QJSEngine.Extension.ConsoleExtension
            :description: QtQml/QJSEngine-Extension-ConsoleExtension-v.rst

        .. sip:enum-member:: PyQt5.QtQml.QJSEngine.Extension.GarbageCollectionExtension
            :description: QtQml/QJSEngine-Extension-GarbageCollectionExtension-v.rst

        .. sip:enum-member:: PyQt5.QtQml.QJSEngine.Extension.TranslationExtension
            :description: QtQml/QJSEngine-Extension-TranslationExtension-v.rst

    .. sip:method:: PyQt5.QtQml.QJSEngine.__init__
        :description: QtQml/QJSEngine-__init__-f.rst

    .. sip:method:: PyQt5.QtQml.QJSEngine.__init__
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
        :description: QtQml/QJSEngine-__init__-f-1.rst

    .. sip:method:: PyQt5.QtQml.QJSEngine.collectGarbage
        :description: QtQml/QJSEngine-collectGarbage-f.rst

    .. sip:method:: PyQt5.QtQml.QJSEngine.evaluate
        :args:
            str
            fileName: str = ''
            lineNumber: int = 1
        :returns:
            :sip:ref:`~PyQt5.QtQml.QJSValue`
        :description: QtQml/QJSEngine-evaluate-f.rst

    .. sip:method:: PyQt5.QtQml.QJSEngine.globalObject
        :returns:
            :sip:ref:`~PyQt5.QtQml.QJSValue`
        :description: QtQml/QJSEngine-globalObject-f.rst

    .. sip:method:: PyQt5.QtQml.QJSEngine.importModule
        :args:
            str
        :returns:
            :sip:ref:`~PyQt5.QtQml.QJSValue`
        :description: QtQml/QJSEngine-importModule-f.rst

    .. sip:method:: PyQt5.QtQml.QJSEngine.installExtensions
        :args:
            Union[:sip:ref:`~PyQt5.QtQml.QJSEngine.Extensions`, :sip:ref:`~PyQt5.QtQml.QJSEngine.Extension`]
            object: Union[:sip:ref:`~PyQt5.QtQml.QJSValue`, :sip:ref:`~PyQt5.QtQml.QJSValue.SpecialValue`, bool, int, float, str] = QJSValue()
        :description: QtQml/QJSEngine-installExtensions-f.rst

    .. sip:method:: PyQt5.QtQml.QJSEngine.installTranslatorFunctions
        :args:
            object: Union[:sip:ref:`~PyQt5.QtQml.QJSValue`, :sip:ref:`~PyQt5.QtQml.QJSValue.SpecialValue`, bool, int, float, str] = QJSValue()
        :description: QtQml/QJSEngine-installTranslatorFunctions-f.rst

    .. sip:method:: PyQt5.QtQml.QJSEngine.newArray
        :args:
            length: int = 0
        :returns:
            :sip:ref:`~PyQt5.QtQml.QJSValue`
        :description: QtQml/QJSEngine-newArray-f.rst

    .. sip:method:: PyQt5.QtQml.QJSEngine.newErrorObject
        :args:
            :sip:ref:`~PyQt5.QtQml.QJSValue.ErrorType`
            message: str = ''
        :returns:
            :sip:ref:`~PyQt5.QtQml.QJSValue`
        :description: QtQml/QJSEngine-newErrorObject-f.rst

    .. sip:method:: PyQt5.QtQml.QJSEngine.newObject
        :returns:
            :sip:ref:`~PyQt5.QtQml.QJSValue`
        :description: QtQml/QJSEngine-newObject-f.rst

    .. sip:method:: PyQt5.QtQml.QJSEngine.newQMetaObject
        :args:
            :sip:ref:`~PyQt5.QtCore.QMetaObject`
        :returns:
            :sip:ref:`~PyQt5.QtQml.QJSValue`
        :description: QtQml/QJSEngine-newQMetaObject-f.rst

    .. sip:method:: PyQt5.QtQml.QJSEngine.newQObject
        :args:
            :sip:ref:`~PyQt5.QtCore.QObject`
        :returns:
            :sip:ref:`~PyQt5.QtQml.QJSValue`
        :description: QtQml/QJSEngine-newQObject-f.rst

    .. sip:method:: PyQt5.QtQml.QJSEngine.throwError
        :args:
            str
        :description: QtQml/QJSEngine-throwError-f.rst

    .. sip:method:: PyQt5.QtQml.QJSEngine.throwError
        :args:
            :sip:ref:`~PyQt5.QtQml.QJSValue.ErrorType`
            message: str = ''
        :description: QtQml/QJSEngine-throwError-f-1.rst
